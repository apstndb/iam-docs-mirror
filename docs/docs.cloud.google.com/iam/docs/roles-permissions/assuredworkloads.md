---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads
title: Assured Workloads roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Assured Workloads. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Assured Workloads roles

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
<td><h4 id="assuredworkloads.admin" class="role-title add-link" data-text="Assured Workloads Administrator" tabindex="-1">Assured Workloads Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p>Grants full access to Assured Workloads resources, CRM resources - project/folder and Organization Policy administration</p></td>
<td><p><code dir="ltr" translate="no">assuredworkloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.updates.list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  updates.  update</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  violations.  get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  violations.  update</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  workload.  create</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  workload.  delete</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.workload.get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.workload.list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  workload.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">axt.labels.set</code></p>
<p><code dir="ltr" translate="no">bigquery.config.update</code></p>
<p><code dir="ltr" translate="no">logging.settings.update</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">orgpolicy.policies.create</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.delete</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">orgpolicy.policy.get</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policy.set</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.editor" class="role-title add-link" data-text="Assured Workloads Editor" tabindex="-1">Assured Workloads Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p>Grants read, write access to Assured Workloads resources, CRM resources - project/folder and Organization Policy administration</p></td>
<td><p><code dir="ltr" translate="no">assuredworkloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.updates.list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  updates.  update</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  violations.  get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  violations.  update</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  workload.  create</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  workload.  delete</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.workload.get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.workload.list</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  workload.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">axt.labels.set</code></p>
<p><code dir="ltr" translate="no">bigquery.config.update</code></p>
<p><code dir="ltr" translate="no">logging.settings.update</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">orgpolicy.policies.create</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.delete</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.list</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">orgpolicy.policy.get</code></li>
<li><code dir="ltr" translate="no">orgpolicy.policy.set</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads.viewer" class="role-title add-link" data-text="Assuredworkloads Viewer" tabindex="-1">Assuredworkloads Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p>Viewer role for assuredworkloads</p></td>
<td><p><code dir="ltr" translate="no">assuredworkloads.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">assuredworkloads.updates.list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  get</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.workload.get</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.workload.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.reader" class="role-title add-link" data-text="Assured Workloads Reader" tabindex="-1">Assured Workloads Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p>Grants read access to all Assured Workloads resources and CRM resources - project/folder</p></td>
<td><p><code dir="ltr" translate="no">assuredworkloads.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  get</code></li>
<li><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">assuredworkloads.updates.list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  get</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.workload.get</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.workload.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
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
<td><h4 id="assuredworkloads.monitoringServiceAgent" class="role-title add-link" data-text="Assured Workloads Monitoring Service Agent" tabindex="-1">Assured Workloads Monitoring Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  assuredworkloads.monitoringServiceAgent</code> )</p>
<p>Gives the Assured Workloads service account access to create CAIS feed and monitor Assured Workloads.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.create</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.delete</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.serviceAgent" class="role-title add-link" data-text="Assured Workloads Service Agent" tabindex="-1">Assured Workloads Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  assuredworkloads.serviceAgent</code> )</p>
<p>Gives the Assured Workloads service account access to create KMS keyrings and keys, monitor Assured Workloads and read Organization Policies.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudkms.cryptoKeys.create</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.create</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Assured Workloads permissions

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
<td><h4 id="assuredworkloads.operations.get" class="permission-name add-link" data-text="assuredworkloads.operations.get" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.operations.list" class="permission-name add-link" data-text="assuredworkloads.operations.list" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads.updates.list" class="permission-name add-link" data-text="assuredworkloads.updates.list" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.updates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.updates.update" class="permission-name add-link" data-text="assuredworkloads.updates.update" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  updates.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads.violations.get" class="permission-name add-link" data-text="assuredworkloads.violations.get" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  violations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringServiceAgent">Cloud Controls Partner Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.violations.list" class="permission-name add-link" data-text="assuredworkloads.violations.list" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringServiceAgent">Cloud Controls Partner Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads.violations.update" class="permission-name add-link" data-text="assuredworkloads.violations.update" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  violations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.workload.create" class="permission-name add-link" data-text="assuredworkloads.workload.create" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  workload.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads.workload.delete" class="permission-name add-link" data-text="assuredworkloads.workload.delete" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  workload.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.workload.get" class="permission-name add-link" data-text="assuredworkloads.workload.get" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.workload.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads.workload.list" class="permission-name add-link" data-text="assuredworkloads.workload.list" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.workload.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="assuredworkloads.workload.update" class="permission-name add-link" data-text="assuredworkloads.workload.update" tabindex="-1"><code dir="ltr" translate="no">assuredworkloads.  workload.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p></td>
</tr>
</tbody>
</table>
