---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery
title: Talent Solution roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Talent Solution. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Talent Solution roles

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
<td><h4 id="cloudjobdiscovery.admin" class="role-title add-link" data-text="Cloud Talent Solution Admin" tabindex="-1">Cloud Talent Solution Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudjobdiscovery.admin</code> )</p>
<p>Access to Cloud Talent Solution Self-Service Tools.</p></td>
<td><p><code dir="ltr" translate="no">cloudjobdiscovery.tools.access</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.viewer" class="role-title add-link" data-text="Cloud Talent Solution Viewer" tabindex="-1">Cloud Talent Solution Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p>Viewer role for Cloud Talent Solution.</p></td>
<td><p><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  get</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  list</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.jobs.get</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.jobs.search</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.profiles.get</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  search</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.tenants.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.jobsEditor" class="role-title add-link" data-text="Cloud Talent Solution Job Editor" tabindex="-1">Cloud Talent Solution Job Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p>Write access to all job data in Cloud Talent Solution.</p></td>
<td><p><code dir="ltr" translate="no">cloudjobdiscovery.companies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  create</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  delete</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  get</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  list</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  events.  create</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudjobdiscovery.jobs.create</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.jobs.delete</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.jobs.get</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.jobs.search</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.jobs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudjobdiscovery.tenants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  create</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  delete</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.tenants.get</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.jobsViewer" class="role-title add-link" data-text="Cloud Talent Solution Job Viewer" tabindex="-1">Cloud Talent Solution Job Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p>Read access to all job data in Cloud Talent Solution.</p></td>
<td><p><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  get</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  list</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.jobs.get</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.jobs.search</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.tenants.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.profilesEditor" class="role-title add-link" data-text="Cloud Talent Solution Profile Editor" tabindex="-1">Cloud Talent Solution Profile Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p>
<p>Write access to all profile data in Cloud Talent Solution.</p></td>
<td><p><code dir="ltr" translate="no">cloudjobdiscovery.  events.  create</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.profiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  create</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  delete</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.profiles.get</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  search</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudjobdiscovery.tenants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  create</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  delete</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.tenants.get</code></li>
<li><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.profilesViewer" class="role-title add-link" data-text="Cloud Talent Solution Profile Viewer" tabindex="-1">Cloud Talent Solution Profile Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesViewer</code> )</p>
<p>Read access to all profile data in Cloud Talent Solution.</p></td>
<td><p><code dir="ltr" translate="no">cloudjobdiscovery.profiles.get</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  search</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.tenants.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Talent Solution permissions

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
<td><h4 id="cloudjobdiscovery.companies.create" class="permission-name add-link" data-text="cloudjobdiscovery.companies.create" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.companies.delete" class="permission-name add-link" data-text="cloudjobdiscovery.companies.delete" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.companies.get" class="permission-name add-link" data-text="cloudjobdiscovery.companies.get" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.companies.list" class="permission-name add-link" data-text="cloudjobdiscovery.companies.list" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.companies.update" class="permission-name add-link" data-text="cloudjobdiscovery.companies.update" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.events.create" class="permission-name add-link" data-text="cloudjobdiscovery.events.create" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  events.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.jobs.create" class="permission-name add-link" data-text="cloudjobdiscovery.jobs.create" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.jobs.delete" class="permission-name add-link" data-text="cloudjobdiscovery.jobs.delete" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.jobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.jobs.get" class="permission-name add-link" data-text="cloudjobdiscovery.jobs.get" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.jobs.search" class="permission-name add-link" data-text="cloudjobdiscovery.jobs.search" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.jobs.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.jobs.update" class="permission-name add-link" data-text="cloudjobdiscovery.jobs.update" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.jobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.profiles.create" class="permission-name add-link" data-text="cloudjobdiscovery.profiles.create" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.profiles.delete" class="permission-name add-link" data-text="cloudjobdiscovery.profiles.delete" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.profiles.get" class="permission-name add-link" data-text="cloudjobdiscovery.profiles.get" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.profiles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.profiles.search" class="permission-name add-link" data-text="cloudjobdiscovery.profiles.search" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.profiles.update" class="permission-name add-link" data-text="cloudjobdiscovery.profiles.update" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  profiles.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.tenants.create" class="permission-name add-link" data-text="cloudjobdiscovery.tenants.create" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.tenants.delete" class="permission-name add-link" data-text="cloudjobdiscovery.tenants.delete" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.tenants.get" class="permission-name add-link" data-text="cloudjobdiscovery.tenants.get" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.tenants.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudjobdiscovery.tenants.update" class="permission-name add-link" data-text="cloudjobdiscovery.tenants.update" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.  tenants.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudjobdiscovery.tools.access" class="permission-name add-link" data-text="cloudjobdiscovery.tools.access" tabindex="-1"><code dir="ltr" translate="no">cloudjobdiscovery.tools.access</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.admin</code> )</p></td>
</tr>
</tbody>
</table>
