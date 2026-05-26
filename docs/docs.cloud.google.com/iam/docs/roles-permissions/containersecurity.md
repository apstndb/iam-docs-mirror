---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/containersecurity
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity
title: Container Security roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Container Security. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Container Security roles

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
<td><h4 id="containersecurity.admin" class="role-title add-link" data-text="Containersecurity Admin Beta" tabindex="-1">Containersecurity Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p>Admin role for containersecurity</p></td>
<td><p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">containersecurity.*</code></p>
<ul>
<li><code dir="ltr" translate="no">containersecurity.  clusterSummaries.  list</code></li>
<li><code dir="ltr" translate="no">containersecurity.  findings.  list</code></li>
<li><code dir="ltr" translate="no">containersecurity.  locations.  get</code></li>
<li><code dir="ltr" translate="no">containersecurity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="containersecurity.viewer" class="role-title add-link" data-text="GKE Security Posture Viewer Beta" tabindex="-1">GKE Security Posture Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p>Read-only access to GKE Security Posture resources.</p></td>
<td><p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">containersecurity.*</code></p>
<ul>
<li><code dir="ltr" translate="no">containersecurity.  clusterSummaries.  list</code></li>
<li><code dir="ltr" translate="no">containersecurity.  findings.  list</code></li>
<li><code dir="ltr" translate="no">containersecurity.  locations.  get</code></li>
<li><code dir="ltr" translate="no">containersecurity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Container Security permissions

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
<td><h4 id="containersecurity.clusterSummaries.list" class="permission-name add-link" data-text="containersecurity.clusterSummaries.list" tabindex="-1"><code dir="ltr" translate="no">containersecurity.  clusterSummaries.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="containersecurity.findings.list" class="permission-name add-link" data-text="containersecurity.findings.list" tabindex="-1"><code dir="ltr" translate="no">containersecurity.  findings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="containersecurity.locations.get" class="permission-name add-link" data-text="containersecurity.locations.get" tabindex="-1"><code dir="ltr" translate="no">containersecurity.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="containersecurity.locations.list" class="permission-name add-link" data-text="containersecurity.locations.list" tabindex="-1"><code dir="ltr" translate="no">containersecurity.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
