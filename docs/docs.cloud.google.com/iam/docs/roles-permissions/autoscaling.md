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
<td><h4 id="autoscaling.admin" class="role-title add-link" data-text="Autoscaling Admin Beta" tabindex="-1">Autoscaling Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p>Admin role for autoscaling</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.*</code></p>
<ul>
<li><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></li>
<li><code dir="ltr" translate="no">autoscaling.sites.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></li>
<li><code dir="ltr" translate="no">autoscaling.sites.writeState</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="autoscaling.editor" class="role-title add-link" data-text="Autoscaling Editor Beta" tabindex="-1">Autoscaling Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p>Editor role for autoscaling</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.writeState</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="autoscaling.viewer" class="role-title add-link" data-text="Autoscaling Viewer Beta" tabindex="-1">Autoscaling Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.viewer</code> )</p>
<p>Viewer role for autoscaling</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="autoscaling.metricsWriter" class="role-title add-link" data-text="Autoscaling Metrics Writer Beta" tabindex="-1">Autoscaling Metrics Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.metricsWriter</code> )</p>
<p>Access to write metrics for autoscaling site</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="autoscaling.recommendationsReader" class="role-title add-link" data-text="Autoscaling Recommendations Reader Beta" tabindex="-1">Autoscaling Recommendations Reader <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.recommendationsReader</code> )</p>
<p>Access to read recommendations from autoscaling site</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></p></td>
</tr>
<tr class="even">
<td><h4 id="autoscaling.sitesAdmin" class="role-title add-link" data-text="Autoscaling Site Admin Beta" tabindex="-1">Autoscaling Site Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p>Full access to all autoscaling site features</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.*</code></p>
<ul>
<li><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></li>
<li><code dir="ltr" translate="no">autoscaling.sites.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></li>
<li><code dir="ltr" translate="no">autoscaling.sites.writeState</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="autoscaling.stateWriter" class="role-title add-link" data-text="Autoscaling State Writer Beta" tabindex="-1">Autoscaling State Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  autoscaling.stateWriter</code> )</p>
<p>Access to write state for autoscaling site</p></td>
<td><p><code dir="ltr" translate="no">autoscaling.sites.writeState</code></p></td>
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
<td><h4 id="autoscaling.sites.getIamPolicy" class="permission-name add-link" data-text="autoscaling.sites.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="autoscaling.sites.readRecommendations" class="permission-name add-link" data-text="autoscaling.sites.readRecommendations" tabindex="-1"><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.recommendationsReader">Autoscaling Recommendations Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.recommendationsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="autoscaling.sites.setIamPolicy" class="permission-name add-link" data-text="autoscaling.sites.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">autoscaling.sites.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="autoscaling.sites.writeMetrics" class="permission-name add-link" data-text="autoscaling.sites.writeMetrics" tabindex="-1"><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.metricsWriter">Autoscaling Metrics Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.metricsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAccount">Kubernetes Engine Default Node Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.defaultNodeServiceAccount</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="autoscaling.sites.writeState" class="permission-name add-link" data-text="autoscaling.sites.writeState" tabindex="-1"><code dir="ltr" translate="no">autoscaling.sites.writeState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.stateWriter">Autoscaling State Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.stateWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
