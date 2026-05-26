---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/transcoder
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder
title: Transcoder API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Transcoder API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Transcoder API roles

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
<td><h4 id="transcoder.admin" class="role-title add-link" data-text="Transcoder Admin" tabindex="-1">Transcoder Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p>Full access to all transcoder resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">transcoder.*</code></p>
<ul>
<li><code dir="ltr" translate="no">transcoder.jobTemplates.create</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobTemplates.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">transcoder.jobTemplates.delete</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobTemplates.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">transcoder.jobTemplates.get</code></li>
<li><code dir="ltr" translate="no">transcoder.jobTemplates.list</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">transcoder.jobs.create</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">transcoder.jobs.delete</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">transcoder.jobs.get</code></li>
<li><code dir="ltr" translate="no">transcoder.jobs.list</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.editor" class="role-title add-link" data-text="Transcoder Editor" tabindex="-1">Transcoder Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p>Editor role for transcoder</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.create</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.delete</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.get</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.list</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.create</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.delete</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.get</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.list</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.viewer" class="role-title add-link" data-text="Transcoder Viewer" tabindex="-1">Transcoder Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p>Viewer of all transcoder resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.get</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.list</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.get</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.list</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></p></td>
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
<td><h4 id="transcoder.serviceAgent" class="role-title add-link" data-text="Transcoder Service Agent" tabindex="-1">Transcoder Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  transcoder.serviceAgent</code> )</p>
<p>Downloads and uploads media files from and to customer Cloud Storage buckets. Publishes status updates to customer Pub/Sub.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.delete</code></p></td>
</tr>
</tbody>
</table>

## Transcoder API permissions

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
<td><h4 id="transcoder.jobTemplates.create" class="permission-name add-link" data-text="transcoder.jobTemplates.create" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobTemplates.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobTemplates.createTagBinding" class="permission-name add-link" data-text="transcoder.jobTemplates.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobTemplates.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobTemplates.delete" class="permission-name add-link" data-text="transcoder.jobTemplates.delete" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobTemplates.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobTemplates.deleteTagBinding" class="permission-name add-link" data-text="transcoder.jobTemplates.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobTemplates.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobTemplates.get" class="permission-name add-link" data-text="transcoder.jobTemplates.get" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobTemplates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobTemplates.list" class="permission-name add-link" data-text="transcoder.jobTemplates.list" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobTemplates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobTemplates.listEffectiveTags" class="permission-name add-link" data-text="transcoder.jobTemplates.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobTemplates.listTagBindings" class="permission-name add-link" data-text="transcoder.jobTemplates.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobs.create" class="permission-name add-link" data-text="transcoder.jobs.create" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mediaasset.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobs.createTagBinding" class="permission-name add-link" data-text="transcoder.jobs.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobs.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobs.delete" class="permission-name add-link" data-text="transcoder.jobs.delete" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mediaasset.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobs.deleteTagBinding" class="permission-name add-link" data-text="transcoder.jobs.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobs.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobs.get" class="permission-name add-link" data-text="transcoder.jobs.get" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset#mediaasset.serviceAgent">Media Asset Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mediaasset.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobs.list" class="permission-name add-link" data-text="transcoder.jobs.list" tabindex="-1"><code dir="ltr" translate="no">transcoder.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder.jobs.listEffectiveTags" class="permission-name add-link" data-text="transcoder.jobs.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transcoder.jobs.listTagBindings" class="permission-name add-link" data-text="transcoder.jobs.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
