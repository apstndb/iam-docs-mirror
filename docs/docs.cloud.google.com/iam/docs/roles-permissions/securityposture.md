---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/securityposture
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture
title: Security Posture API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Security Posture API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Security Posture API roles

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
<td><h4 id="securityposture.admin" class="role-title add-link" data-text="Security Posture Admin" tabindex="-1">Security Posture Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p>Full access to Security Posture service APIs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">orgpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">orgpolicy.constraints.list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  create</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  delete</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  get</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  update</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.create</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.delete</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.update</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policy.get</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policy.set</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></p>
<p><code dir="ltr" translate="no">securityposture.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.locations.get</code></li>
<li><code dir="ltr" translate="no">securityposture.locations.list</code></li>
<li><code dir="ltr" translate="no">securityposture.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securityposture.operations.get</code></li>
<li><code dir="ltr" translate="no">securityposture.  operations.  list</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  create</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  update</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  create</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  delete</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  extract</code></li>
<li><code dir="ltr" translate="no">securityposture.postures.get</code></li>
<li><code dir="ltr" translate="no">securityposture.postures.list</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  update</code></li>
<li><code dir="ltr" translate="no">securityposture.reports.create</code></li>
<li><code dir="ltr" translate="no">securityposture.reports.get</code></li>
<li><code dir="ltr" translate="no">securityposture.reports.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.viewer" class="role-title add-link" data-text="Security Posture Viewer" tabindex="-1">Security Posture Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p>Read only access to all the SecurityPosture Service resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securityposture.postures.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postureDeployer" class="role-title add-link" data-text="Security Posture Deployer" tabindex="-1">Security Posture Deployer</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Mutate and read permissions to the Posture Deployment resource.</p></td>
<td><p><code dir="ltr" translate="no">orgpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">orgpolicy.constraints.list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  create</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  delete</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  get</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.  customConstraints.  update</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.create</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.delete</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.update</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policy.get</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policy.set</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  create</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureDeployments.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postureDeploymentsViewer" class="role-title add-link" data-text="Security Posture Deployments Viewer" tabindex="-1">Security Posture Deployments Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.postureDeploymentsViewer</code> )</p>
<p>Read only access to the Posture Deployment resource.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postureEditor" class="role-title add-link" data-text="Security Posture Resource Editor" tabindex="-1">Security Posture Resource Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p>
<p>Mutate and read permissions to the Posture resource.</p></td>
<td><p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.  postures.  create</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  delete</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  extract</code></li>
<li><code dir="ltr" translate="no">securityposture.postures.get</code></li>
<li><code dir="ltr" translate="no">securityposture.postures.list</code></li>
<li><code dir="ltr" translate="no">securityposture.  postures.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postureViewer" class="role-title add-link" data-text="Security Posture Resource Viewer" tabindex="-1">Security Posture Resource Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.postureViewer</code> )</p>
<p>Read only access to the Posture resource.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.reportCreator" class="role-title add-link" data-text="Security Posture Shift-Left Validator" tabindex="-1">Security Posture Shift-Left Validator</h4>
<p>( <code dir="ltr" translate="no">roles/  securityposture.reportCreator</code> )</p>
<p>Create access for Reports, e.g. IaC Validation Report.</p></td>
<td><p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.reports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.reports.create</code></li>
<li><code dir="ltr" translate="no">securityposture.reports.get</code></li>
<li><code dir="ltr" translate="no">securityposture.reports.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Security Posture API permissions

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
<td><h4 id="securityposture.locations.get" class="permission-name add-link" data-text="securityposture.locations.get" tabindex="-1"><code dir="ltr" translate="no">securityposture.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.locations.list" class="permission-name add-link" data-text="securityposture.locations.list" tabindex="-1"><code dir="ltr" translate="no">securityposture.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.operations.delete" class="permission-name add-link" data-text="securityposture.operations.delete" tabindex="-1"><code dir="ltr" translate="no">securityposture.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.operations.get" class="permission-name add-link" data-text="securityposture.operations.get" tabindex="-1"><code dir="ltr" translate="no">securityposture.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeploymentsViewer">Security Posture Deployments Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeploymentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureViewer">Security Posture Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.reportCreator">Security Posture Shift-Left Validator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.reportCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.operations.list" class="permission-name add-link" data-text="securityposture.operations.list" tabindex="-1"><code dir="ltr" translate="no">securityposture.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postureDeployments.create" class="permission-name add-link" data-text="securityposture.postureDeployments.create" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureDeployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postureDeployments.delete" class="permission-name add-link" data-text="securityposture.postureDeployments.delete" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureDeployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postureDeployments.get" class="permission-name add-link" data-text="securityposture.postureDeployments.get" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeploymentsViewer">Security Posture Deployments Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeploymentsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postureDeployments.list" class="permission-name add-link" data-text="securityposture.postureDeployments.list" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeploymentsViewer">Security Posture Deployments Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeploymentsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postureDeployments.update" class="permission-name add-link" data-text="securityposture.postureDeployments.update" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureDeployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postureTemplates.get" class="permission-name add-link" data-text="securityposture.postureTemplates.get" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureTemplates.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postureTemplates.list" class="permission-name add-link" data-text="securityposture.postureTemplates.list" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postures.create" class="permission-name add-link" data-text="securityposture.postures.create" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postures.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postures.delete" class="permission-name add-link" data-text="securityposture.postures.delete" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postures.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postures.extract" class="permission-name add-link" data-text="securityposture.postures.extract" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postures.  extract</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postures.get" class="permission-name add-link" data-text="securityposture.postures.get" tabindex="-1"><code dir="ltr" translate="no">securityposture.postures.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureViewer">Security Posture Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.postures.list" class="permission-name add-link" data-text="securityposture.postures.list" tabindex="-1"><code dir="ltr" translate="no">securityposture.postures.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureViewer">Security Posture Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.postures.update" class="permission-name add-link" data-text="securityposture.postures.update" tabindex="-1"><code dir="ltr" translate="no">securityposture.  postures.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureEditor">Security Posture Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.reports.create" class="permission-name add-link" data-text="securityposture.reports.create" tabindex="-1"><code dir="ltr" translate="no">securityposture.reports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.reportCreator">Security Posture Shift-Left Validator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.reportCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securityposture.reports.get" class="permission-name add-link" data-text="securityposture.reports.get" tabindex="-1"><code dir="ltr" translate="no">securityposture.reports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.reportCreator">Security Posture Shift-Left Validator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.reportCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securityposture.reports.list" class="permission-name add-link" data-text="securityposture.reports.list" tabindex="-1"><code dir="ltr" translate="no">securityposture.reports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.reportCreator">Security Posture Shift-Left Validator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.reportCreator</code> )</p></td>
</tr>
</tbody>
</table>
