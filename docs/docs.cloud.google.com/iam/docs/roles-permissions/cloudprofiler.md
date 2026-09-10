---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler
title: Cloud Profiler roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Profiler. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Profiler roles

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
<td><h4 id="cloudprofiler.admin" class="role-title add-link" data-text="Cloud Profiler Admin" tabindex="-1">Cloud Profiler Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprofiler.admin</code> )</p>
<p>Admin role for Cloud Profiler</p></td>
<td><p><code dir="ltr" translate="no">cloudprofiler.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudprofiler.profiles.create</code></li>
<li><code dir="ltr" translate="no">cloudprofiler.profiles.list</code></li>
<li><code dir="ltr" translate="no">cloudprofiler.profiles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprofiler.viewer" class="role-title add-link" data-text="Cloud Profiler Viewer" tabindex="-1">Cloud Profiler Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprofiler.viewer</code> )</p>
<p>Viewer role for Cloud Profiler</p></td>
<td><p><code dir="ltr" translate="no">cloudprofiler.profiles.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprofiler.agent" class="role-title add-link" data-text="Cloud Profiler Agent" tabindex="-1">Cloud Profiler Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprofiler.agent</code> )</p>
<p>Cloud Profiler agents are allowed to register and provide the profiling data.</p></td>
<td><p><code dir="ltr" translate="no">cloudprofiler.profiles.create</code></p>
<p><code dir="ltr" translate="no">cloudprofiler.profiles.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprofiler.user" class="role-title add-link" data-text="Cloud Profiler User" tabindex="-1">Cloud Profiler User</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudprofiler.user</code> )</p>
<p>Cloud Profiler users are allowed to query and view the profiling data.</p></td>
<td><p><code dir="ltr" translate="no">cloudprofiler.profiles.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Cloud Profiler permissions

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
<td><h4 id="cloudprofiler.profiles.create" class="permission-name add-link" data-text="cloudprofiler.profiles.create" tabindex="-1"><code dir="ltr" translate="no">cloudprofiler.profiles.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.agent">Cloud Profiler Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudprofiler.profiles.list" class="permission-name add-link" data-text="cloudprofiler.profiles.list" tabindex="-1"><code dir="ltr" translate="no">cloudprofiler.profiles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.viewer">Cloud Profiler Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudprofiler.profiles.update" class="permission-name add-link" data-text="cloudprofiler.profiles.update" tabindex="-1"><code dir="ltr" translate="no">cloudprofiler.profiles.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.agent">Cloud Profiler Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p></td>
</tr>
</tbody>
</table>
