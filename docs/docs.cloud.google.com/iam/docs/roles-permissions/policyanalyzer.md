---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer
title: Policy Analyzer roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Policy Analyzer. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Policy Analyzer roles

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
<td><h4 id="policyanalyzer.admin" class="role-title add-link" data-text="Policyanalyzer Admin Beta" tabindex="-1">Policyanalyzer Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyanalyzer.admin</code> )</p>
<p>Admin role for policyanalyzer</p></td>
<td><p><code dir="ltr" translate="no">policyanalyzer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyanalyzer.  resourceAuthorizationActivities.  query</code></li>
<li><code dir="ltr" translate="no">policyanalyzer.  serviceAccountKeyLastAuthenticationActivities.  query</code></li>
<li><code dir="ltr" translate="no">policyanalyzer.  serviceAccountLastAuthenticationActivities.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="policyanalyzer.viewer" class="role-title add-link" data-text="Policyanalyzer Viewer Beta" tabindex="-1">Policyanalyzer Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyanalyzer.viewer</code> )</p>
<p>Viewer role for policyanalyzer</p></td>
<td><p><code dir="ltr" translate="no">policyanalyzer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyanalyzer.  resourceAuthorizationActivities.  query</code></li>
<li><code dir="ltr" translate="no">policyanalyzer.  serviceAccountKeyLastAuthenticationActivities.  query</code></li>
<li><code dir="ltr" translate="no">policyanalyzer.  serviceAccountLastAuthenticationActivities.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="policyanalyzer.activityAnalysisViewer" class="role-title add-link" data-text="Activity Analysis Viewer Beta" tabindex="-1">Activity Analysis Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyanalyzer.activityAnalysisViewer</code> )</p>
<p>Viewer user that can read all activity analysis.</p></td>
<td><p><code dir="ltr" translate="no">policyanalyzer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyanalyzer.  resourceAuthorizationActivities.  query</code></li>
<li><code dir="ltr" translate="no">policyanalyzer.  serviceAccountKeyLastAuthenticationActivities.  query</code></li>
<li><code dir="ltr" translate="no">policyanalyzer.  serviceAccountLastAuthenticationActivities.  query</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Policy Analyzer permissions

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
<td><h4 id="policyanalyzer.resourceAuthorizationActivities.query" class="permission-name add-link" data-text="policyanalyzer.resourceAuthorizationActivities.query" tabindex="-1"><code dir="ltr" translate="no">policyanalyzer.  resourceAuthorizationActivities.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.activityAnalysisViewer">Activity Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.activityAnalysisViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policyanalyzer.serviceAccountKeyLastAuthenticationActivities.query" class="permission-name add-link" data-text="policyanalyzer.serviceAccountKeyLastAuthenticationActivities.query" tabindex="-1"><code dir="ltr" translate="no">policyanalyzer.  serviceAccountKeyLastAuthenticationActivities.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.activityAnalysisViewer">Activity Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.activityAnalysisViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policyanalyzer.serviceAccountLastAuthenticationActivities.query" class="permission-name add-link" data-text="policyanalyzer.serviceAccountLastAuthenticationActivities.query" tabindex="-1"><code dir="ltr" translate="no">policyanalyzer.  serviceAccountLastAuthenticationActivities.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.activityAnalysisViewer">Activity Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.activityAnalysisViewer</code> )</p></td>
</tr>
</tbody>
</table>
