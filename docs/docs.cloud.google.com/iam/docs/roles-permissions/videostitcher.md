---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/videostitcher
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher
title: Video Stitcher API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Video Stitcher API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Video Stitcher API roles

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
<td><h4 id="videostitcher.admin" class="role-title add-link" data-text="Video Stitcher Admin" tabindex="-1">Video Stitcher Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p>Full access to all video stitcher resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.*</code></p>
<ul>
<li><code dir="ltr" translate="no">videostitcher.cdnKeys.create</code></li>
<li><code dir="ltr" translate="no">videostitcher.cdnKeys.delete</code></li>
<li><code dir="ltr" translate="no">videostitcher.cdnKeys.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.cdnKeys.list</code></li>
<li><code dir="ltr" translate="no">videostitcher.cdnKeys.update</code></li>
<li><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  list</code></li>
<li><code dir="ltr" translate="no">videostitcher.  liveConfigs.  create</code></li>
<li><code dir="ltr" translate="no">videostitcher.  liveConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">videostitcher.liveConfigs.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.liveConfigs.list</code></li>
<li><code dir="ltr" translate="no">videostitcher.  liveSessions.  create</code></li>
<li><code dir="ltr" translate="no">videostitcher.liveSessions.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">videostitcher.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">videostitcher.operations.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.operations.list</code></li>
<li><code dir="ltr" translate="no">videostitcher.slates.create</code></li>
<li><code dir="ltr" translate="no">videostitcher.slates.delete</code></li>
<li><code dir="ltr" translate="no">videostitcher.slates.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.slates.list</code></li>
<li><code dir="ltr" translate="no">videostitcher.slates.update</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  list</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodConfigs.  create</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">videostitcher.vodConfigs.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.vodConfigs.list</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodConfigs.  update</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodSessions.  create</code></li>
<li><code dir="ltr" translate="no">videostitcher.vodSessions.get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.viewer" class="role-title add-link" data-text="Video Stitcher Viewer" tabindex="-1">Video Stitcher Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p>Read-only access to video stitcher resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.cdnKeys.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.cdnKeys.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">videostitcher.liveConfigs.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.liveConfigs.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.liveSessions.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.operations.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.operations.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.slates.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.slates.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">videostitcher.vodConfigs.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.vodConfigs.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.vodSessions.get</code></p>
<p><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  get</code></li>
<li><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.user" class="role-title add-link" data-text="Video Stitcher User" tabindex="-1">Video Stitcher User</h4>
<p>( <code dir="ltr" translate="no">roles/  videostitcher.user</code> )</p>
<p>Full access to video stitcher sessions.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.liveSessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">videostitcher.  liveSessions.  create</code></li>
<li><code dir="ltr" translate="no">videostitcher.liveSessions.get</code></li>
</ul>
<p><code dir="ltr" translate="no">videostitcher.vodSessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">videostitcher.  vodSessions.  create</code></li>
<li><code dir="ltr" translate="no">videostitcher.vodSessions.get</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Video Stitcher API permissions

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
<td><h4 id="videostitcher.cdnKeys.create" class="permission-name add-link" data-text="videostitcher.cdnKeys.create" tabindex="-1"><code dir="ltr" translate="no">videostitcher.cdnKeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.cdnKeys.delete" class="permission-name add-link" data-text="videostitcher.cdnKeys.delete" tabindex="-1"><code dir="ltr" translate="no">videostitcher.cdnKeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.cdnKeys.get" class="permission-name add-link" data-text="videostitcher.cdnKeys.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.cdnKeys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.cdnKeys.list" class="permission-name add-link" data-text="videostitcher.cdnKeys.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.cdnKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.cdnKeys.update" class="permission-name add-link" data-text="videostitcher.cdnKeys.update" tabindex="-1"><code dir="ltr" translate="no">videostitcher.cdnKeys.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.liveAdTagDetails.get" class="permission-name add-link" data-text="videostitcher.liveAdTagDetails.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.liveAdTagDetails.list" class="permission-name add-link" data-text="videostitcher.liveAdTagDetails.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.liveConfigs.create" class="permission-name add-link" data-text="videostitcher.liveConfigs.create" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  liveConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.liveConfigs.delete" class="permission-name add-link" data-text="videostitcher.liveConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  liveConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.liveConfigs.get" class="permission-name add-link" data-text="videostitcher.liveConfigs.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.liveConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.liveConfigs.list" class="permission-name add-link" data-text="videostitcher.liveConfigs.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.liveConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.liveSessions.create" class="permission-name add-link" data-text="videostitcher.liveSessions.create" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  liveSessions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.liveSessions.get" class="permission-name add-link" data-text="videostitcher.liveSessions.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.liveSessions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.operations.cancel" class="permission-name add-link" data-text="videostitcher.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.operations.delete" class="permission-name add-link" data-text="videostitcher.operations.delete" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.operations.get" class="permission-name add-link" data-text="videostitcher.operations.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.operations.list" class="permission-name add-link" data-text="videostitcher.operations.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.slates.create" class="permission-name add-link" data-text="videostitcher.slates.create" tabindex="-1"><code dir="ltr" translate="no">videostitcher.slates.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.slates.delete" class="permission-name add-link" data-text="videostitcher.slates.delete" tabindex="-1"><code dir="ltr" translate="no">videostitcher.slates.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.slates.get" class="permission-name add-link" data-text="videostitcher.slates.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.slates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.slates.list" class="permission-name add-link" data-text="videostitcher.slates.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.slates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.slates.update" class="permission-name add-link" data-text="videostitcher.slates.update" tabindex="-1"><code dir="ltr" translate="no">videostitcher.slates.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.vodAdTagDetails.get" class="permission-name add-link" data-text="videostitcher.vodAdTagDetails.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.vodAdTagDetails.list" class="permission-name add-link" data-text="videostitcher.vodAdTagDetails.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.vodConfigs.create" class="permission-name add-link" data-text="videostitcher.vodConfigs.create" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.vodConfigs.delete" class="permission-name add-link" data-text="videostitcher.vodConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.vodConfigs.get" class="permission-name add-link" data-text="videostitcher.vodConfigs.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.vodConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.vodConfigs.list" class="permission-name add-link" data-text="videostitcher.vodConfigs.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.vodConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.vodConfigs.update" class="permission-name add-link" data-text="videostitcher.vodConfigs.update" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.vodSessions.create" class="permission-name add-link" data-text="videostitcher.vodSessions.create" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodSessions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.vodSessions.get" class="permission-name add-link" data-text="videostitcher.vodSessions.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.vodSessions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="videostitcher.vodStitchDetails.get" class="permission-name add-link" data-text="videostitcher.vodStitchDetails.get" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="videostitcher.vodStitchDetails.list" class="permission-name add-link" data-text="videostitcher.vodStitchDetails.list" tabindex="-1"><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
