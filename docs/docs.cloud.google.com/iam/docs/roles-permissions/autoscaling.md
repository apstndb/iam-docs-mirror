---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/autoscaling
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling
title: Cloud Autoscaling roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Autoscaling. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Autoscaling roles

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
<td>Autoscaling Admin <sup>Beta</sup>
<p>( <code>roles/ autoscaling.admin</code> )</p>
<p>Admin role for autoscaling</p></td>
<td><p><code>autoscaling.*</code></p>
<ul>
<li><code>autoscaling.sites.getIamPolicy</code></li>
<li><code>autoscaling. sites. readRecommendations</code></li>
<li><code>autoscaling.sites.setIamPolicy</code></li>
<li><code>autoscaling.sites.writeMetrics</code></li>
<li><code>autoscaling.sites.writeState</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Autoscaling Editor <sup>Beta</sup>
<p>( <code>roles/ autoscaling.editor</code> )</p>
<p>Editor role for autoscaling</p></td>
<td><p><code>autoscaling.sites.getIamPolicy</code></p>
<p><code>autoscaling. sites. readRecommendations</code></p>
<p><code>autoscaling.sites.writeMetrics</code></p>
<p><code>autoscaling.sites.writeState</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Autoscaling Viewer <sup>Beta</sup>
<p>( <code>roles/ autoscaling.viewer</code> )</p>
<p>Viewer role for autoscaling</p></td>
<td><p><code>autoscaling.sites.getIamPolicy</code></p>
<p><code>autoscaling. sites. readRecommendations</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Autoscaling Metrics Writer <sup>Beta</sup>
<p>( <code>roles/ autoscaling.metricsWriter</code> )</p>
<p>Access to write metrics for autoscaling site</p></td>
<td><p><code>autoscaling.sites.writeMetrics</code></p></td>
</tr>
<tr class="odd">
<td>Autoscaling Recommendations Reader <sup>Beta</sup>
<p>( <code>roles/ autoscaling.recommendationsReader</code> )</p>
<p>Access to read recommendations from autoscaling site</p></td>
<td><p><code>autoscaling. sites. readRecommendations</code></p></td>
</tr>
<tr class="even">
<td>Autoscaling Site Admin <sup>Beta</sup>
<p>( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p>Full access to all autoscaling site features</p></td>
<td><p><code>autoscaling.*</code></p>
<ul>
<li><code>autoscaling.sites.getIamPolicy</code></li>
<li><code>autoscaling. sites. readRecommendations</code></li>
<li><code>autoscaling.sites.setIamPolicy</code></li>
<li><code>autoscaling.sites.writeMetrics</code></li>
<li><code>autoscaling.sites.writeState</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Autoscaling State Writer <sup>Beta</sup>
<p>( <code>roles/ autoscaling.stateWriter</code> )</p>
<p>Access to write state for autoscaling site</p></td>
<td><p><code>autoscaling.sites.writeState</code></p></td>
</tr>
</tbody>
</table>

## Cloud Autoscaling permissions

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
<td><code>autoscaling.sites.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code>roles/ autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code>roles/ autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>autoscaling. sites. readRecommendations</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code>roles/ autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code>roles/ autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.recommendationsReader">Autoscaling Recommendations Reader</a> ( <code>roles/ autoscaling.recommendationsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>autoscaling.sites.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>autoscaling.sites.writeMetrics</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code>roles/ autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.metricsWriter">Autoscaling Metrics Writer</a> ( <code>roles/ autoscaling.metricsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAccount">Kubernetes Engine Default Node Service Account</a> ( <code>roles/ container.defaultNodeServiceAccount</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code>roles/ rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>autoscaling.sites.writeState</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code>roles/ autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.stateWriter">Autoscaling State Writer</a> ( <code>roles/ autoscaling.stateWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
