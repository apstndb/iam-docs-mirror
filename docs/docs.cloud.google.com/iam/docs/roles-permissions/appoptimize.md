---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/appoptimize
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize
title: App Optimize API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for App Optimize API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## App Optimize API roles

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
<td><h4 id="appoptimize.admin" class="role-title add-link" data-text="App Optimize Admin Beta" tabindex="-1">App Optimize Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p>Lets you create, read, update, and delete App Optimize resources.</p></td>
<td><p><code dir="ltr" translate="no">appoptimize.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appoptimize.locations.get</code></li>
<li><code dir="ltr" translate="no">appoptimize.locations.list</code></li>
<li><code dir="ltr" translate="no">appoptimize.operations.cancel</code></li>
<li><code dir="ltr" translate="no">appoptimize.operations.delete</code></li>
<li><code dir="ltr" translate="no">appoptimize.operations.get</code></li>
<li><code dir="ltr" translate="no">appoptimize.operations.list</code></li>
<li><code dir="ltr" translate="no">appoptimize.reports.create</code></li>
<li><code dir="ltr" translate="no">appoptimize.reports.delete</code></li>
<li><code dir="ltr" translate="no">appoptimize.reports.get</code></li>
<li><code dir="ltr" translate="no">appoptimize.reports.getData</code></li>
<li><code dir="ltr" translate="no">appoptimize.reports.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appoptimize.viewer" class="role-title add-link" data-text="App Optimize Viewer Beta" tabindex="-1">App Optimize Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p>Lets you read App Optimize resources.</p></td>
<td><p><code dir="ltr" translate="no">appoptimize.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appoptimize.locations.get</code></li>
<li><code dir="ltr" translate="no">appoptimize.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appoptimize.operations.get</code></p>
<p><code dir="ltr" translate="no">appoptimize.operations.list</code></p>
<p><code dir="ltr" translate="no">appoptimize.reports.get</code></p>
<p><code dir="ltr" translate="no">appoptimize.reports.getData</code></p>
<p><code dir="ltr" translate="no">appoptimize.reports.list</code></p></td>
</tr>
</tbody>
</table>

## App Optimize API permissions

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
<td><h4 id="appoptimize.locations.get" class="permission-name add-link" data-text="appoptimize.locations.get" tabindex="-1"><code dir="ltr" translate="no">appoptimize.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="appoptimize.locations.list" class="permission-name add-link" data-text="appoptimize.locations.list" tabindex="-1"><code dir="ltr" translate="no">appoptimize.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appoptimize.operations.cancel" class="permission-name add-link" data-text="appoptimize.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">appoptimize.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="appoptimize.operations.delete" class="permission-name add-link" data-text="appoptimize.operations.delete" tabindex="-1"><code dir="ltr" translate="no">appoptimize.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appoptimize.operations.get" class="permission-name add-link" data-text="appoptimize.operations.get" tabindex="-1"><code dir="ltr" translate="no">appoptimize.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="appoptimize.operations.list" class="permission-name add-link" data-text="appoptimize.operations.list" tabindex="-1"><code dir="ltr" translate="no">appoptimize.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appoptimize.reports.create" class="permission-name add-link" data-text="appoptimize.reports.create" tabindex="-1"><code dir="ltr" translate="no">appoptimize.reports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="appoptimize.reports.delete" class="permission-name add-link" data-text="appoptimize.reports.delete" tabindex="-1"><code dir="ltr" translate="no">appoptimize.reports.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appoptimize.reports.get" class="permission-name add-link" data-text="appoptimize.reports.get" tabindex="-1"><code dir="ltr" translate="no">appoptimize.reports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="appoptimize.reports.getData" class="permission-name add-link" data-text="appoptimize.reports.getData" tabindex="-1"><code dir="ltr" translate="no">appoptimize.reports.getData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appoptimize.reports.list" class="permission-name add-link" data-text="appoptimize.reports.list" tabindex="-1"><code dir="ltr" translate="no">appoptimize.reports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.admin">App Optimize Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appoptimize#appoptimize.viewer">App Optimize Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appoptimize.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
