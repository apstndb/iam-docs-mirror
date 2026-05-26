---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager
title: Workload Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Workload Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Workload Manager roles

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
<td><h4 id="workloadmanager.admin" class="role-title add-link" data-text="Workload Manager Admin Beta" tabindex="-1">Workload Manager Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p>Full access to Workload Manager all resources.</p></td>
<td><p><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.actuations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  getHealth</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  run</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  update</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  executions.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.executions.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  insights.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  insights.  export</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  insights.  listSapSystems</code></li>
<li><code dir="ltr" translate="no">workloadmanager.insights.write</code></li>
<li><code dir="ltr" translate="no">workloadmanager.locations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.locations.list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.results.list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.rules.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.viewer" class="role-title add-link" data-text="Workload Manager Viewer Beta" tabindex="-1">Workload Manager Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p>Read-only access to Workload Manager all resources.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.actuations.get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  getHealth</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.  evaluations.  get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.executions.get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.results.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.rules.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.deploymentAdmin" class="role-title add-link" data-text="Workload Manager Deployment Admin Beta" tabindex="-1">Workload Manager Deployment Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p>Full access to Workload Manager deployment resources.</p></td>
<td><p><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.actuations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.actuations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.locations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.deploymentViewer" class="role-title add-link" data-text="Workload Manager Deployment Viewer Beta" tabindex="-1">Workload Manager Deployment Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p>Read-only access to Workload Manager deployment resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.actuations.get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.evaluationAdmin" class="role-title add-link" data-text="Workload Manager Evaluation Admin Beta" tabindex="-1">Workload Manager Evaluation Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p>Full access to Workload Manager evaluation resources.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.evaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  run</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  executions.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.executions.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.locations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.results.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.rules.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.evaluationViewer" class="role-title add-link" data-text="Workload Manager Evaluation Viewer Beta" tabindex="-1">Workload Manager Evaluation Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p>Read-only access to Workload Manager evaluation resources.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  evaluations.  get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.executions.get</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.results.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.rules.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.insightWriter" class="role-title add-link" data-text="Workload Manager Insights Writer Beta" tabindex="-1">Workload Manager Insights Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.insightWriter</code> )</p>
<p>The role used to write data to WLM data warehouse.</p></td>
<td><p><code dir="ltr" translate="no">workloadmanager.  insights.  delete</code></p>
<p><code dir="ltr" translate="no">workloadmanager.insights.write</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.worker" class="role-title add-link" data-text="Workload Manager Worker Beta" tabindex="-1">Workload Manager Worker <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p>
<p>The role used by Workload Manager application runners to read and update workloads.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.actuations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.actuations.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  getHealth</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.evaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  create</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  run</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  evaluations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  executions.  delete</code></li>
<li><code dir="ltr" translate="no">workloadmanager.executions.get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadmanager.insights.write</code></p>
<p><code dir="ltr" translate="no">workloadmanager.results.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.rules.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.workloadViewer" class="role-title add-link" data-text="Workload Manager Workload Viewer Beta" tabindex="-1">Workload Manager Workload Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.workloadViewer</code> )</p>
<p>The role used to view the workload related data.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  get</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  getHealth</code></li>
<li><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></li>
</ul></td>
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
<td><h4 id="workloadmanager.serviceAgent" class="role-title add-link" data-text="Workload Manager Service Agent" tabindex="-1">Workload Manager Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</p>
<p>Gives Workload Manager Service Agent access to CAI export functions and Cloud Monitoring.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  exportAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">config.deployments.create</code></p>
<p><code dir="ltr" translate="no">config.deployments.delete</code></p>
<p><code dir="ltr" translate="no">config.deployments.get</code></p>
<p><code dir="ltr" translate="no">config.deployments.list</code></p>
<p><code dir="ltr" translate="no">config.deployments.update</code></p>
<p><code dir="ltr" translate="no">config.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.locations.get</code></li>
<li><code dir="ltr" translate="no">config.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.operations.cancel</code></li>
<li><code dir="ltr" translate="no">config.operations.delete</code></li>
<li><code dir="ltr" translate="no">config.operations.get</code></li>
<li><code dir="ltr" translate="no">config.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.resources.list</code></p>
<p><code dir="ltr" translate="no">config.revisions.get</code></p>
<p><code dir="ltr" translate="no">config.revisions.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  insights.  export</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  insights.  listSapSystems</code></p></td>
</tr>
</tbody>
</table>

## Workload Manager permissions

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
<td><h4 id="workloadmanager.actuations.create" class="permission-name add-link" data-text="workloadmanager.actuations.create" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  actuations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.actuations.delete" class="permission-name add-link" data-text="workloadmanager.actuations.delete" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  actuations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.actuations.get" class="permission-name add-link" data-text="workloadmanager.actuations.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.actuations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.actuations.list" class="permission-name add-link" data-text="workloadmanager.actuations.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.deployments.create" class="permission-name add-link" data-text="workloadmanager.deployments.create" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  deployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.deployments.delete" class="permission-name add-link" data-text="workloadmanager.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  deployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.deployments.get" class="permission-name add-link" data-text="workloadmanager.deployments.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  deployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.deployments.list" class="permission-name add-link" data-text="workloadmanager.deployments.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.discoveredprofiles.get" class="permission-name add-link" data-text="workloadmanager.discoveredprofiles.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.workloadViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.discoveredprofiles.getHealth" class="permission-name add-link" data-text="workloadmanager.discoveredprofiles.getHealth" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  getHealth</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.workloadViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.discoveredprofiles.list" class="permission-name add-link" data-text="workloadmanager.discoveredprofiles.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.workloadViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.evaluations.create" class="permission-name add-link" data-text="workloadmanager.evaluations.create" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  evaluations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.evaluations.delete" class="permission-name add-link" data-text="workloadmanager.evaluations.delete" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  evaluations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.evaluations.get" class="permission-name add-link" data-text="workloadmanager.evaluations.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  evaluations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.evaluations.list" class="permission-name add-link" data-text="workloadmanager.evaluations.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.evaluations.run" class="permission-name add-link" data-text="workloadmanager.evaluations.run" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  evaluations.  run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.evaluations.update" class="permission-name add-link" data-text="workloadmanager.evaluations.update" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  evaluations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.executions.delete" class="permission-name add-link" data-text="workloadmanager.executions.delete" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  executions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.executions.get" class="permission-name add-link" data-text="workloadmanager.executions.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.executions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.executions.list" class="permission-name add-link" data-text="workloadmanager.executions.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.insights.delete" class="permission-name add-link" data-text="workloadmanager.insights.delete" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  insights.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.insightWriter">Workload Manager Insights Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.insightWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.insights.export" class="permission-name add-link" data-text="workloadmanager.insights.export" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  insights.  export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.insights.listSapSystems" class="permission-name add-link" data-text="workloadmanager.insights.listSapSystems" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  insights.  listSapSystems</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.insights.write" class="permission-name add-link" data-text="workloadmanager.insights.write" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.insights.write</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.insightWriter">Workload Manager Insights Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.insightWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.locations.get" class="permission-name add-link" data-text="workloadmanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.locations.list" class="permission-name add-link" data-text="workloadmanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.operations.cancel" class="permission-name add-link" data-text="workloadmanager.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.operations.delete" class="permission-name add-link" data-text="workloadmanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.operations.get" class="permission-name add-link" data-text="workloadmanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.operations.list" class="permission-name add-link" data-text="workloadmanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadmanager.results.list" class="permission-name add-link" data-text="workloadmanager.results.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.results.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadmanager.rules.list" class="permission-name add-link" data-text="workloadmanager.rules.list" tabindex="-1"><code dir="ltr" translate="no">workloadmanager.rules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p></td>
</tr>
</tbody>
</table>
