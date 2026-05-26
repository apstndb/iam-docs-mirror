---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights
title: Service Security Insights roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Security Insights. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Security Insights roles

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
<td><h4 id="servicesecurityinsights.securityInsightsViewer" class="role-title add-link" data-text="Security Insights Viewer Beta" tabindex="-1">Security Insights Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p>
<p>Read-only access to Security Insights resources</p></td>
<td><p><code dir="ltr" translate="no">servicesecurityinsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicesecurityinsights.  clusterSecurityInfo.  get</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  clusterSecurityInfo.  list</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  policies.  get</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  projectStates.  get</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  securityInfo.  list</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  securityViews.  get</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  workloadPolicies.  list</code></li>
<li><code dir="ltr" translate="no">servicesecurityinsights.  workloadSecurityInfo.  get</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Service Security Insights permissions

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
<td><h4 id="servicesecurityinsights.clusterSecurityInfo.get" class="permission-name add-link" data-text="servicesecurityinsights.clusterSecurityInfo.get" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  clusterSecurityInfo.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicesecurityinsights.clusterSecurityInfo.list" class="permission-name add-link" data-text="servicesecurityinsights.clusterSecurityInfo.list" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  clusterSecurityInfo.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicesecurityinsights.policies.get" class="permission-name add-link" data-text="servicesecurityinsights.policies.get" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  policies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicesecurityinsights.projectStates.get" class="permission-name add-link" data-text="servicesecurityinsights.projectStates.get" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  projectStates.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicesecurityinsights.securityInfo.list" class="permission-name add-link" data-text="servicesecurityinsights.securityInfo.list" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  securityInfo.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicesecurityinsights.securityViews.get" class="permission-name add-link" data-text="servicesecurityinsights.securityViews.get" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  securityViews.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicesecurityinsights.workloadPolicies.list" class="permission-name add-link" data-text="servicesecurityinsights.workloadPolicies.list" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  workloadPolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicesecurityinsights.workloadSecurityInfo.get" class="permission-name add-link" data-text="servicesecurityinsights.workloadSecurityInfo.get" tabindex="-1"><code dir="ltr" translate="no">servicesecurityinsights.  workloadSecurityInfo.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicesecurityinsights#servicesecurityinsights.securityInsightsViewer">Security Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicesecurityinsights.securityInsightsViewer</code> )</p></td>
</tr>
</tbody>
</table>
