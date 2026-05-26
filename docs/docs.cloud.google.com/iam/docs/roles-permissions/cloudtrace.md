---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace
title: Cloud Trace roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Trace. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Trace roles

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
<td><h4 id="cloudtrace.admin" class="role-title add-link" data-text="Cloud Trace Admin" tabindex="-1">Cloud Trace Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p>Provides full access to the Trace console and read-write access to traces.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudtrace.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtrace.insights.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.insights.list</code></li>
<li><code dir="ltr" translate="no">cloudtrace.stats.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.create</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.delete</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.list</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.create</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.delete</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.update</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traces.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traces.list</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traces.patch</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  traceScopes.  create</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  delete</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">telemetry.traces.write</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.user" class="role-title add-link" data-text="Cloud Trace User" tabindex="-1">Cloud Trace User</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p>Provides full access to the Trace console and read access to traces.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudtrace.insights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtrace.insights.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.insights.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtrace.stats.get</code></p>
<p><code dir="ltr" translate="no">cloudtrace.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtrace.tasks.create</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.delete</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtrace.traceScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.create</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.delete</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">cloudtrace.traceScopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtrace.traces.get</code></p>
<p><code dir="ltr" translate="no">cloudtrace.traces.list</code></p>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  traceScopes.  create</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  delete</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.agent" class="role-title add-link" data-text="Cloud Trace Agent" tabindex="-1">Cloud Trace Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtrace.agent</code> )</p>
<p>For service accounts. Provides ability to write traces by sending the data to Stackdriver Trace.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudtrace.traces.patch</code></p>
<p><code dir="ltr" translate="no">telemetry.traces.write</code></p></td>
</tr>
</tbody>
</table>

## Cloud Trace permissions

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
<td><h4 id="cloudtrace.insights.get" class="permission-name add-link" data-text="cloudtrace.insights.get" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.insights.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.insights.list" class="permission-name add-link" data-text="cloudtrace.insights.list" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.insights.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.stats.get" class="permission-name add-link" data-text="cloudtrace.stats.get" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.stats.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.tasks.create" class="permission-name add-link" data-text="cloudtrace.tasks.create" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.tasks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.tasks.delete" class="permission-name add-link" data-text="cloudtrace.tasks.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.tasks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.tasks.get" class="permission-name add-link" data-text="cloudtrace.tasks.get" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.tasks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.tasks.list" class="permission-name add-link" data-text="cloudtrace.tasks.list" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.tasks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.traceScopes.create" class="permission-name add-link" data-text="cloudtrace.traceScopes.create" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traceScopes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.traceScopes.delete" class="permission-name add-link" data-text="cloudtrace.traceScopes.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traceScopes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.traceScopes.get" class="permission-name add-link" data-text="cloudtrace.traceScopes.get" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traceScopes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.traceScopes.list" class="permission-name add-link" data-text="cloudtrace.traceScopes.list" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traceScopes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.traceScopes.update" class="permission-name add-link" data-text="cloudtrace.traceScopes.update" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traceScopes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.traces.get" class="permission-name add-link" data-text="cloudtrace.traces.get" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtrace.traces.list" class="permission-name add-link" data-text="cloudtrace.traces.list" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traces.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtrace.traces.patch" class="permission-name add-link" data-text="cloudtrace.traces.patch" tabindex="-1"><code dir="ltr" translate="no">cloudtrace.traces.patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.agent">Cloud Trace Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsDataPlaneServiceAgent">KubeRun Events Data Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kuberun.eventsDataPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.notificationServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
