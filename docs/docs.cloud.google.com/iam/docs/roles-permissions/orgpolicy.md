---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy
title: Organization Policy Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Organization Policy Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Organization Policy Service roles

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
<td>Organization Policy Administrator
<p>( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p>Provides access to define what restrictions an organization wants to place on the configuration of cloud resources by setting Organization Policies.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>cloudasset. assets. analyzeOrgPolicy</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>orgpolicy.*</code></p>
<ul>
<li><code>orgpolicy.constraints.list</code></li>
<li><code>orgpolicy. customConstraints. create</code></li>
<li><code>orgpolicy. customConstraints. delete</code></li>
<li><code>orgpolicy. customConstraints. get</code></li>
<li><code>orgpolicy. customConstraints. list</code></li>
<li><code>orgpolicy. customConstraints. update</code></li>
<li><code>orgpolicy.policies.create</code></li>
<li><code>orgpolicy.policies.delete</code></li>
<li><code>orgpolicy.policies.list</code></li>
<li><code>orgpolicy.policies.update</code></li>
<li><code>orgpolicy.policy.get</code></li>
<li><code>orgpolicy.policy.set</code></li>
</ul>
<p><code>policysimulator. orgPolicyViolations. list</code></p>
<p><code>policysimulator. orgPolicyViolationsPreviews.*</code></p>
<ul>
<li><code>policysimulator. orgPolicyViolationsPreviews. create</code></li>
<li><code>policysimulator. orgPolicyViolationsPreviews. get</code></li>
<li><code>policysimulator. orgPolicyViolationsPreviews. list</code></li>
</ul>
<p><code>recommender. orgPolicyInsights.*</code></p>
<ul>
<li><code>recommender. orgPolicyInsights. get</code></li>
<li><code>recommender. orgPolicyInsights. list</code></li>
<li><code>recommender. orgPolicyInsights. update</code></li>
</ul>
<p><code>recommender. orgPolicyRecommendations.*</code></p>
<ul>
<li><code>recommender. orgPolicyRecommendations. get</code></li>
<li><code>recommender. orgPolicyRecommendations. list</code></li>
<li><code>recommender. orgPolicyRecommendations. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Organization Policy Viewer
<p>( <code>roles/ orgpolicy.policyViewer</code> )</p>
<p>Provides access to view Organization Policies on resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy. customConstraints. get</code></p>
<p><code>orgpolicy. customConstraints. list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p></td>
</tr>
</tbody>
</table>

## Organization Policy Service permissions

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
<td><code>orgpolicy.constraints.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyViewer">Organization Policy Viewer</a> ( <code>roles/ orgpolicy.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>orgpolicy. customConstraints. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>orgpolicy. customConstraints. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="even">
<td><code>orgpolicy. customConstraints. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyViewer">Organization Policy Viewer</a> ( <code>roles/ orgpolicy.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code>roles/ policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>orgpolicy. customConstraints. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyViewer">Organization Policy Viewer</a> ( <code>roles/ orgpolicy.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code>roles/ policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>orgpolicy. customConstraints. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>orgpolicy.policies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="even">
<td><code>orgpolicy.policies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>orgpolicy.policies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyViewer">Organization Policy Viewer</a> ( <code>roles/ orgpolicy.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code>roles/ policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>orgpolicy.policies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>orgpolicy.policy.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyViewer">Organization Policy Viewer</a> ( <code>roles/ orgpolicy.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code>roles/ policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.apiKeysAdmin">API Keys Admin</a> ( <code>roles/ serviceusage.apiKeysAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code>roles/ workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.expressModeUserAccess">Storage Express Mode User Access</a> ( <code>roles/ storage.expressModeUserAccess</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code>roles/ workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code>roles/ workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code>roles/ workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>orgpolicy.policy.set</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code>roles/ orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p></td>
</tr>
</tbody>
</table>
