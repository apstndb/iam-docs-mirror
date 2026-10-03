---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/speakerid
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid
title: Speaker ID roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Speaker ID. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Speaker ID roles

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
<td>Speaker ID Admin
<p>( <code>roles/ speakerid.admin</code> )</p>
<p>Grants full access to all Speaker ID resources, including project settings.</p></td>
<td><p><code>speakerid.*</code></p>
<ul>
<li><code>speakerid.phrases.create</code></li>
<li><code>speakerid.phrases.delete</code></li>
<li><code>speakerid.phrases.get</code></li>
<li><code>speakerid.phrases.list</code></li>
<li><code>speakerid.settings.get</code></li>
<li><code>speakerid.settings.update</code></li>
<li><code>speakerid.speakers.create</code></li>
<li><code>speakerid.speakers.delete</code></li>
<li><code>speakerid.speakers.get</code></li>
<li><code>speakerid.speakers.list</code></li>
<li><code>speakerid.speakers.verify</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Speaker ID Editor
<p>( <code>roles/ speakerid.editor</code> )</p>
<p>Grants access to read and write all Speaker ID resources.</p></td>
<td><p><code>speakerid.phrases.*</code></p>
<ul>
<li><code>speakerid.phrases.create</code></li>
<li><code>speakerid.phrases.delete</code></li>
<li><code>speakerid.phrases.get</code></li>
<li><code>speakerid.phrases.list</code></li>
</ul>
<p><code>speakerid.speakers.*</code></p>
<ul>
<li><code>speakerid.speakers.create</code></li>
<li><code>speakerid.speakers.delete</code></li>
<li><code>speakerid.speakers.get</code></li>
<li><code>speakerid.speakers.list</code></li>
<li><code>speakerid.speakers.verify</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Speaker ID Viewer
<p>( <code>roles/ speakerid.viewer</code> )</p>
<p>Grants read access to all Speaker ID resources.</p></td>
<td><p><code>speakerid.phrases.get</code></p>
<p><code>speakerid.phrases.list</code></p>
<p><code>speakerid.speakers.get</code></p>
<p><code>speakerid.speakers.list</code></p></td>
</tr>
<tr class="even">
<td>Speaker ID Verifier
<p>( <code>roles/ speakerid.verifier</code> )</p>
<p>Grants read access to all Speaker ID resources, and allows verification.</p></td>
<td><p><code>speakerid.phrases.get</code></p>
<p><code>speakerid.phrases.list</code></p>
<p><code>speakerid.speakers.get</code></p>
<p><code>speakerid.speakers.list</code></p>
<p><code>speakerid.speakers.verify</code></p></td>
</tr>
</tbody>
</table>

## Speaker ID permissions

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
<td><code>speakerid.phrases.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>speakerid.phrases.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>speakerid.phrases.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code>roles/ speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code>roles/ speakerid.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>speakerid.phrases.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code>roles/ speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code>roles/ speakerid.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>speakerid.settings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>speakerid.settings.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>speakerid.speakers.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>speakerid.speakers.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>speakerid.speakers.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code>roles/ speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code>roles/ speakerid.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>speakerid.speakers.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code>roles/ speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code>roles/ speakerid.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>speakerid.speakers.verify</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code>roles/ speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code>roles/ speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code>roles/ speakerid.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
