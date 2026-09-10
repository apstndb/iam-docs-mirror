---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing
title: Confidential Computing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Confidential Computing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Confidential Computing roles

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
<td><h4 id="confidentialcomputing.admin" class="role-title add-link" data-text="Confidentialcomputing Admin" tabindex="-1">Confidentialcomputing Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p>Admin role for confidentialcomputing</p></td>
<td><p><code dir="ltr" translate="no">confidentialcomputing.*</code></p>
<ul>
<li><code dir="ltr" translate="no">confidentialcomputing.  challenges.  create</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  challenges.  verify</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  challenges.  verifygke</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  get</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="confidentialcomputing.viewer" class="role-title add-link" data-text="Confidentialcomputing Viewer" tabindex="-1">Confidentialcomputing Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  confidentialcomputing.viewer</code> )</p>
<p>Viewer role for confidentialcomputing</p></td>
<td><p><code dir="ltr" translate="no">confidentialcomputing.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  get</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="confidentialcomputing.gkeWorkloadUser" class="role-title add-link" data-text="Confidential GKE Workload User" tabindex="-1">Confidential GKE Workload User</h4>
<p>( <code dir="ltr" translate="no">roles/  confidentialcomputing.gkeWorkloadUser</code> )</p>
<p>Grants the ability to generate a GKE attestation token and run a workload in a GKE cluster.</p></td>
<td><p><code dir="ltr" translate="no">confidentialcomputing.  challenges.  create</code></p>
<p><code dir="ltr" translate="no">confidentialcomputing.  challenges.  verifygke</code></p>
<p><code dir="ltr" translate="no">confidentialcomputing.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  get</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p></td>
</tr>
<tr class="even">
<td><h4 id="confidentialcomputing.workloadUser" class="role-title add-link" data-text="Confidential Space Workload User" tabindex="-1">Confidential Space Workload User</h4>
<p>( <code dir="ltr" translate="no">roles/  confidentialcomputing.workloadUser</code> )</p>
<p>Grants the ability to generate an attestation token and run a workload in a VM. Intended for service accounts that run on Confidential Space VMs.</p></td>
<td><p><code dir="ltr" translate="no">confidentialcomputing.  challenges.  create</code></p>
<p><code dir="ltr" translate="no">confidentialcomputing.  challenges.  verify</code></p>
<p><code dir="ltr" translate="no">confidentialcomputing.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  get</code></li>
<li><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p></td>
</tr>
</tbody>
</table>

## Confidential Computing permissions

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
<td><h4 id="confidentialcomputing.challenges.create" class="permission-name add-link" data-text="confidentialcomputing.challenges.create" tabindex="-1"><code dir="ltr" translate="no">confidentialcomputing.  challenges.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser">Confidential GKE Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.gkeWorkloadUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser">Confidential Space Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.workloadUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="confidentialcomputing.challenges.verify" class="permission-name add-link" data-text="confidentialcomputing.challenges.verify" tabindex="-1"><code dir="ltr" translate="no">confidentialcomputing.  challenges.  verify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser">Confidential Space Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.workloadUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="confidentialcomputing.challenges.verifygke" class="permission-name add-link" data-text="confidentialcomputing.challenges.verifygke" tabindex="-1"><code dir="ltr" translate="no">confidentialcomputing.  challenges.  verifygke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser">Confidential GKE Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.gkeWorkloadUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="confidentialcomputing.locations.get" class="permission-name add-link" data-text="confidentialcomputing.locations.get" tabindex="-1"><code dir="ltr" translate="no">confidentialcomputing.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer">Confidentialcomputing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser">Confidential GKE Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.gkeWorkloadUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser">Confidential Space Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.workloadUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="confidentialcomputing.locations.list" class="permission-name add-link" data-text="confidentialcomputing.locations.list" tabindex="-1"><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer">Confidentialcomputing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser">Confidential GKE Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.gkeWorkloadUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser">Confidential Space Workload User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.workloadUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
