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
<td><h4 id="osconfig.admin" class="role-title add-link" data-text="OS Config Admin" tabindex="-1">OS Config Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p>Full access to OS Config resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.create</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.delete</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.get</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.update</code></li>
<li><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.inventories.get</code></li>
<li><code dir="ltr" translate="no">osconfig.inventories.list</code></li>
<li><code dir="ltr" translate="no">osconfig.locations.get</code></li>
<li><code dir="ltr" translate="no">osconfig.locations.list</code></li>
<li><code dir="ltr" translate="no">osconfig.operations.cancel</code></li>
<li><code dir="ltr" translate="no">osconfig.operations.delete</code></li>
<li><code dir="ltr" translate="no">osconfig.operations.get</code></li>
<li><code dir="ltr" translate="no">osconfig.operations.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  searchSummaries</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  create</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  delete</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  searchPolicies</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  update</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  create</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  execute</code></li>
<li><code dir="ltr" translate="no">osconfig.patchDeployments.get</code></li>
<li><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  pause</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  resume</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  update</code></li>
<li><code dir="ltr" translate="no">osconfig.patchJobs.exec</code></li>
<li><code dir="ltr" translate="no">osconfig.patchJobs.get</code></li>
<li><code dir="ltr" translate="no">osconfig.patchJobs.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  create</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  delete</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  update</code></li>
<li><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  update</code></li>
<li><code dir="ltr" translate="no">osconfig.upgradeReports.get</code></li>
<li><code dir="ltr" translate="no">osconfig.  upgradeReports.  getSummary</code></li>
<li><code dir="ltr" translate="no">osconfig.upgradeReports.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  upgradeReports.  searchSummaries</code></li>
<li><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.viewer" class="role-title add-link" data-text="OS Config Viewer" tabindex="-1">OS Config Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p>Readonly access to OS Config resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.guestPolicies.get</code></p>
<p><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.inventories.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.inventories.get</code></li>
<li><code dir="ltr" translate="no">osconfig.inventories.list</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.locations.get</code></li>
<li><code dir="ltr" translate="no">osconfig.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.operations.get</code></p>
<p><code dir="ltr" translate="no">osconfig.operations.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  searchSummaries</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  searchPolicies</code></p>
<p><code dir="ltr" translate="no">osconfig.patchDeployments.get</code></p>
<p><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></p>
<p><code dir="ltr" translate="no">osconfig.patchJobs.get</code></p>
<p><code dir="ltr" translate="no">osconfig.patchJobs.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.upgradeReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.upgradeReports.get</code></li>
<li><code dir="ltr" translate="no">osconfig.  upgradeReports.  getSummary</code></li>
<li><code dir="ltr" translate="no">osconfig.upgradeReports.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  upgradeReports.  searchSummaries</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.guestPolicyAdmin" class="role-title add-link" data-text="GuestPolicy Admin Beta" tabindex="-1">GuestPolicy Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p>
<p>Full admin access to GuestPolicies</p></td>
<td><p><code dir="ltr" translate="no">osconfig.guestPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.create</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.delete</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.get</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></li>
<li><code dir="ltr" translate="no">osconfig.guestPolicies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.guestPolicyEditor" class="role-title add-link" data-text="GuestPolicy Editor Beta" tabindex="-1">GuestPolicy Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.guestPolicyEditor</code> )</p>
<p>Editor of GuestPolicy resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.guestPolicies.get</code></p>
<p><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></p>
<p><code dir="ltr" translate="no">osconfig.guestPolicies.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.guestPolicyViewer" class="role-title add-link" data-text="GuestPolicy Viewer Beta" tabindex="-1">GuestPolicy Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.guestPolicyViewer</code> )</p>
<p>Viewer of GuestPolicy resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.guestPolicies.get</code></p>
<p><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.instanceOSPoliciesComplianceViewer" class="role-title add-link" data-text="InstanceOSPoliciesCompliance Viewer Beta" tabindex="-1">InstanceOSPoliciesCompliance Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p>Viewer of OS Policies Compliance of VM instances</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.inventoryViewer" class="role-title add-link" data-text="OS Inventory Viewer" tabindex="-1">OS Inventory Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.inventoryViewer</code> )</p>
<p>Viewer of OS Inventories</p></td>
<td><p><code dir="ltr" translate="no">osconfig.inventories.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.inventories.get</code></li>
<li><code dir="ltr" translate="no">osconfig.inventories.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignmentAdmin" class="role-title add-link" data-text="OSPolicyAssignment Admin" tabindex="-1">OSPolicyAssignment Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p>Full admin access to OS Policy Assignments</p></td>
<td><p><code dir="ltr" translate="no">osconfig.osPolicyAssignments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  create</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  delete</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  searchPolicies</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.osPolicyAssignmentEditor" class="role-title add-link" data-text="OSPolicyAssignment Editor" tabindex="-1">OSPolicyAssignment Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p>Editor of OS Policy Assignments</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  searchPolicies</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignmentReportViewer" class="role-title add-link" data-text="OSPolicyAssignmentReport Viewer" tabindex="-1">OSPolicyAssignmentReport Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p>Viewer of OS policy assignment reports for VM instances</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  searchSummaries</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.osPolicyAssignmentViewer" class="role-title add-link" data-text="OSPolicyAssignment Viewer" tabindex="-1">OSPolicyAssignment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentViewer</code> )</p>
<p>Viewer of OS Policy Assignments</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  searchPolicies</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchDeploymentAdmin" class="role-title add-link" data-text="PatchDeployment Admin" tabindex="-1">PatchDeployment Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p>
<p>Full admin access to PatchDeployments</p></td>
<td><p><code dir="ltr" translate="no">osconfig.patchDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  create</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  execute</code></li>
<li><code dir="ltr" translate="no">osconfig.patchDeployments.get</code></li>
<li><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  pause</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  resume</code></li>
<li><code dir="ltr" translate="no">osconfig.  patchDeployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchDeploymentViewer" class="role-title add-link" data-text="PatchDeployment Viewer" tabindex="-1">PatchDeployment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.patchDeploymentViewer</code> )</p>
<p>Viewer of PatchDeployment resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.patchDeployments.get</code></p>
<p><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchJobExecutor" class="role-title add-link" data-text="Patch Job Executor" tabindex="-1">Patch Job Executor</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.patchJobExecutor</code> )</p>
<p>Access to execute Patch Jobs.</p></td>
<td><p><code dir="ltr" translate="no">osconfig.patchJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.patchJobs.exec</code></li>
<li><code dir="ltr" translate="no">osconfig.patchJobs.get</code></li>
<li><code dir="ltr" translate="no">osconfig.patchJobs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchJobViewer" class="role-title add-link" data-text="Patch Job Viewer" tabindex="-1">Patch Job Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.patchJobViewer</code> )</p>
<p>Get and list Patch Jobs.</p></td>
<td><p><code dir="ltr" translate="no">osconfig.patchJobs.get</code></p>
<p><code dir="ltr" translate="no">osconfig.patchJobs.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.policyOrchestratorAdmin" class="role-title add-link" data-text="PolicyOrchestrator Admin Beta" tabindex="-1">PolicyOrchestrator Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p>
<p>Admin of PolicyOrchestrator resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.locations.get</code></li>
<li><code dir="ltr" translate="no">osconfig.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.operations.get</code></p>
<p><code dir="ltr" translate="no">osconfig.policyOrchestrators.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  create</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  delete</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></li>
<li><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.policyOrchestratorViewer" class="role-title add-link" data-text="PolicyOrchestrator Viewer Beta" tabindex="-1">PolicyOrchestrator Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.policyOrchestratorViewer</code> )</p>
<p>Viewer of PolicyOrchestrator resources</p></td>
<td><p><code dir="ltr" translate="no">osconfig.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.locations.get</code></li>
<li><code dir="ltr" translate="no">osconfig.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">osconfig.operations.get</code></p>
<p><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.projectFeatureSettingsEditor" class="role-title add-link" data-text="Project Feature Settings Editor" tabindex="-1">Project Feature Settings Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsEditor</code> )</p>
<p>Read/write access to project feature settings</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.projectFeatureSettingsViewer" class="role-title add-link" data-text="Project Feature Settings Viewer" tabindex="-1">Project Feature Settings Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsViewer</code> )</p>
<p>Read access to project feature settings</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.upgradeReportViewer" class="role-title add-link" data-text="Upgrade Report Viewer Beta" tabindex="-1">Upgrade Report Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p>
<p>Provides read-only access to VM Manager Upgrade Reports</p></td>
<td><p><code dir="ltr" translate="no">osconfig.upgradeReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.upgradeReports.get</code></li>
<li><code dir="ltr" translate="no">osconfig.  upgradeReports.  getSummary</code></li>
<li><code dir="ltr" translate="no">osconfig.upgradeReports.list</code></li>
<li><code dir="ltr" translate="no">osconfig.  upgradeReports.  searchSummaries</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.vulnerabilityReportViewer" class="role-title add-link" data-text="OS VulnerabilityReport Viewer" tabindex="-1">OS VulnerabilityReport Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.vulnerabilityReportViewer</code> )</p>
<p>Viewer of OS VulnerabilityReports</p></td>
<td><p><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="osconfig.rolloutServiceAgent" class="role-title add-link" data-text="Cloud OS Config Rollout Service Agent" tabindex="-1">Cloud OS Config Rollout Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.rolloutServiceAgent</code> )</p>
<p>Grants OS Config Rollout Service Account access to zonal OS Config resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">osconfig.operations.get</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  delete</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.serviceAgent" class="role-title add-link" data-text="Cloud OS Config Service Agent" tabindex="-1">Cloud OS Config Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</p>
<p>Grants OS Config Service Account access to Google Compute Engine instances.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigOSPolicyAssignments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listPatchDeployments</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setCommonInstanceMetadata</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  attachOccurrence</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.update</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  get</code></li>
<li><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="osconfig.guestPolicies.create" class="permission-name add-link" data-text="osconfig.guestPolicies.create" tabindex="-1"><code dir="ltr" translate="no">osconfig.guestPolicies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.guestPolicies.delete" class="permission-name add-link" data-text="osconfig.guestPolicies.delete" tabindex="-1"><code dir="ltr" translate="no">osconfig.guestPolicies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.guestPolicies.get" class="permission-name add-link" data-text="osconfig.guestPolicies.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.guestPolicies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.guestPolicies.list" class="permission-name add-link" data-text="osconfig.guestPolicies.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.guestPolicies.update" class="permission-name add-link" data-text="osconfig.guestPolicies.update" tabindex="-1"><code dir="ltr" translate="no">osconfig.guestPolicies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.instanceOSPoliciesCompliances.get" class="permission-name add-link" data-text="osconfig.instanceOSPoliciesCompliances.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.instanceOSPoliciesComplianceViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.instanceOSPoliciesCompliances.list" class="permission-name add-link" data-text="osconfig.instanceOSPoliciesCompliances.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.instanceOSPoliciesComplianceViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.inventories.get" class="permission-name add-link" data-text="osconfig.inventories.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.inventories.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.inventoryViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.inventories.list" class="permission-name add-link" data-text="osconfig.inventories.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.inventories.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.inventoryViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.locations.get" class="permission-name add-link" data-text="osconfig.locations.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.locations.list" class="permission-name add-link" data-text="osconfig.locations.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.operations.cancel" class="permission-name add-link" data-text="osconfig.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">osconfig.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.operations.delete" class="permission-name add-link" data-text="osconfig.operations.delete" tabindex="-1"><code dir="ltr" translate="no">osconfig.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.operations.get" class="permission-name add-link" data-text="osconfig.operations.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.operations.list" class="permission-name add-link" data-text="osconfig.operations.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignmentReports.get" class="permission-name add-link" data-text="osconfig.osPolicyAssignmentReports.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentReportViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.osPolicyAssignmentReports.list" class="permission-name add-link" data-text="osconfig.osPolicyAssignmentReports.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentReportViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignmentReports.searchSummaries" class="permission-name add-link" data-text="osconfig.osPolicyAssignmentReports.searchSummaries" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  searchSummaries</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentReportViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.osPolicyAssignments.create" class="permission-name add-link" data-text="osconfig.osPolicyAssignments.create" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignments.delete" class="permission-name add-link" data-text="osconfig.osPolicyAssignments.delete" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.osPolicyAssignments.get" class="permission-name add-link" data-text="osconfig.osPolicyAssignments.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignments.list" class="permission-name add-link" data-text="osconfig.osPolicyAssignments.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.osPolicyAssignments.searchPolicies" class="permission-name add-link" data-text="osconfig.osPolicyAssignments.searchPolicies" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  searchPolicies</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.osPolicyAssignments.update" class="permission-name add-link" data-text="osconfig.osPolicyAssignments.update" tabindex="-1"><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchDeployments.create" class="permission-name add-link" data-text="osconfig.patchDeployments.create" tabindex="-1"><code dir="ltr" translate="no">osconfig.  patchDeployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchDeployments.delete" class="permission-name add-link" data-text="osconfig.patchDeployments.delete" tabindex="-1"><code dir="ltr" translate="no">osconfig.  patchDeployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchDeployments.execute" class="permission-name add-link" data-text="osconfig.patchDeployments.execute" tabindex="-1"><code dir="ltr" translate="no">osconfig.  patchDeployments.  execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchDeployments.get" class="permission-name add-link" data-text="osconfig.patchDeployments.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.patchDeployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchDeployments.list" class="permission-name add-link" data-text="osconfig.patchDeployments.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchDeployments.pause" class="permission-name add-link" data-text="osconfig.patchDeployments.pause" tabindex="-1"><code dir="ltr" translate="no">osconfig.  patchDeployments.  pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchDeployments.resume" class="permission-name add-link" data-text="osconfig.patchDeployments.resume" tabindex="-1"><code dir="ltr" translate="no">osconfig.  patchDeployments.  resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchDeployments.update" class="permission-name add-link" data-text="osconfig.patchDeployments.update" tabindex="-1"><code dir="ltr" translate="no">osconfig.  patchDeployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchJobs.exec" class="permission-name add-link" data-text="osconfig.patchJobs.exec" tabindex="-1"><code dir="ltr" translate="no">osconfig.patchJobs.exec</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobExecutor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.patchJobs.get" class="permission-name add-link" data-text="osconfig.patchJobs.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.patchJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.patchJobs.list" class="permission-name add-link" data-text="osconfig.patchJobs.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.patchJobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.policyOrchestrators.create" class="permission-name add-link" data-text="osconfig.policyOrchestrators.create" tabindex="-1"><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.policyOrchestrators.delete" class="permission-name add-link" data-text="osconfig.policyOrchestrators.delete" tabindex="-1"><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.policyOrchestrators.get" class="permission-name add-link" data-text="osconfig.policyOrchestrators.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.policyOrchestrators.list" class="permission-name add-link" data-text="osconfig.policyOrchestrators.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.policyOrchestrators.update" class="permission-name add-link" data-text="osconfig.policyOrchestrators.update" tabindex="-1"><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.policyOrchestratorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.projectFeatureSettings.get" class="permission-name add-link" data-text="osconfig.projectFeatureSettings.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsViewer">Project Feature Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.projectFeatureSettings.update" class="permission-name add-link" data-text="osconfig.projectFeatureSettings.update" tabindex="-1"><code dir="ltr" translate="no">osconfig.  projectFeatureSettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.upgradeReports.get" class="permission-name add-link" data-text="osconfig.upgradeReports.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.upgradeReports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.upgradeReports.getSummary" class="permission-name add-link" data-text="osconfig.upgradeReports.getSummary" tabindex="-1"><code dir="ltr" translate="no">osconfig.  upgradeReports.  getSummary</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.upgradeReports.list" class="permission-name add-link" data-text="osconfig.upgradeReports.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.upgradeReports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.upgradeReports.searchSummaries" class="permission-name add-link" data-text="osconfig.upgradeReports.searchSummaries" tabindex="-1"><code dir="ltr" translate="no">osconfig.  upgradeReports.  searchSummaries</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="osconfig.vulnerabilityReports.get" class="permission-name add-link" data-text="osconfig.vulnerabilityReports.get" tabindex="-1"><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.vulnerabilityReportViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="osconfig.vulnerabilityReports.list" class="permission-name add-link" data-text="osconfig.vulnerabilityReports.list" tabindex="-1"><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.vulnerabilityReportViewer</code> )</p></td>
</tr>
</tbody>
</table>
