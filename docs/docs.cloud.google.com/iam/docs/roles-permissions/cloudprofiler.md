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
<td>Cloud Profiler Admin
<p>( <code>roles/ cloudprofiler.admin</code> )</p>
<p>Admin role for Cloud Profiler</p></td>
<td><p><code>cloudprofiler.*</code></p>
<ul>
<li><code>cloudprofiler.profiles.create</code></li>
<li><code>cloudprofiler.profiles.list</code></li>
<li><code>cloudprofiler.profiles.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Profiler Viewer
<p>( <code>roles/ cloudprofiler.viewer</code> )</p>
<p>Viewer role for Cloud Profiler</p></td>
<td><p><code>cloudprofiler.profiles.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Profiler Agent
<p>( <code>roles/ cloudprofiler.agent</code> )</p>
<p>Cloud Profiler agents are allowed to register and provide the profiling data.</p></td>
<td><p><code>cloudprofiler.profiles.create</code></p>
<p><code>cloudprofiler.profiles.update</code></p></td>
</tr>
<tr class="even">
<td>Cloud Profiler User
<p>( <code>roles/ cloudprofiler.user</code> )</p>
<p>Cloud Profiler users are allowed to query and view the profiling data.</p></td>
<td><p><code>cloudprofiler.profiles.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Cloud Profiler permissions

| Permission                      | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `cloudprofiler.profiles.create` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Profiler Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin) ( `roles/ cloudprofiler.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Profiler Agent](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.agent) ( `roles/ cloudprofiler.agent` ) [Dataproc Worker](https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker) ( `roles/ dataproc.worker` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `cloudprofiler.profiles.list`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Profiler Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin) ( `roles/ cloudprofiler.admin` ) [Cloud Profiler Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.viewer) ( `roles/ cloudprofiler.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Profiler User](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user) ( `roles/ cloudprofiler.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `cloudprofiler.profiles.update` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Profiler Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin) ( `roles/ cloudprofiler.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Profiler Agent](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.agent) ( `roles/ cloudprofiler.agent` ) [Dataproc Worker](https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker) ( `roles/ dataproc.worker` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
