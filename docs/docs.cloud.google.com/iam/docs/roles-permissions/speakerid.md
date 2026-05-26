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
<td><h4 id="speakerid.admin" class="role-title add-link" data-text="Speaker ID Admin" tabindex="-1">Speaker ID Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p>Grants full access to all Speaker ID resources, including project settings.</p></td>
<td><p><code dir="ltr" translate="no">speakerid.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speakerid.phrases.create</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.delete</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.get</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.list</code></li>
<li><code dir="ltr" translate="no">speakerid.settings.get</code></li>
<li><code dir="ltr" translate="no">speakerid.settings.update</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.create</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.delete</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.get</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.list</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.verify</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.editor" class="role-title add-link" data-text="Speaker ID Editor" tabindex="-1">Speaker ID Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p>Grants access to read and write all Speaker ID resources.</p></td>
<td><p><code dir="ltr" translate="no">speakerid.phrases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speakerid.phrases.create</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.delete</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.get</code></li>
<li><code dir="ltr" translate="no">speakerid.phrases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">speakerid.speakers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speakerid.speakers.create</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.delete</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.get</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.list</code></li>
<li><code dir="ltr" translate="no">speakerid.speakers.verify</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speakerid.viewer" class="role-title add-link" data-text="Speaker ID Viewer" tabindex="-1">Speaker ID Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  speakerid.viewer</code> )</p>
<p>Grants read access to all Speaker ID resources.</p></td>
<td><p><code dir="ltr" translate="no">speakerid.phrases.get</code></p>
<p><code dir="ltr" translate="no">speakerid.phrases.list</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.get</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.verifier" class="role-title add-link" data-text="Speaker ID Verifier" tabindex="-1">Speaker ID Verifier</h4>
<p>( <code dir="ltr" translate="no">roles/  speakerid.verifier</code> )</p>
<p>Grants read access to all Speaker ID resources, and allows verification.</p></td>
<td><p><code dir="ltr" translate="no">speakerid.phrases.get</code></p>
<p><code dir="ltr" translate="no">speakerid.phrases.list</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.get</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.list</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.verify</code></p></td>
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
<td><h4 id="speakerid.phrases.create" class="permission-name add-link" data-text="speakerid.phrases.create" tabindex="-1"><code dir="ltr" translate="no">speakerid.phrases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.phrases.delete" class="permission-name add-link" data-text="speakerid.phrases.delete" tabindex="-1"><code dir="ltr" translate="no">speakerid.phrases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speakerid.phrases.get" class="permission-name add-link" data-text="speakerid.phrases.get" tabindex="-1"><code dir="ltr" translate="no">speakerid.phrases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.verifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.phrases.list" class="permission-name add-link" data-text="speakerid.phrases.list" tabindex="-1"><code dir="ltr" translate="no">speakerid.phrases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.verifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speakerid.settings.get" class="permission-name add-link" data-text="speakerid.settings.get" tabindex="-1"><code dir="ltr" translate="no">speakerid.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.settings.update" class="permission-name add-link" data-text="speakerid.settings.update" tabindex="-1"><code dir="ltr" translate="no">speakerid.settings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speakerid.speakers.create" class="permission-name add-link" data-text="speakerid.speakers.create" tabindex="-1"><code dir="ltr" translate="no">speakerid.speakers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.speakers.delete" class="permission-name add-link" data-text="speakerid.speakers.delete" tabindex="-1"><code dir="ltr" translate="no">speakerid.speakers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speakerid.speakers.get" class="permission-name add-link" data-text="speakerid.speakers.get" tabindex="-1"><code dir="ltr" translate="no">speakerid.speakers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.verifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speakerid.speakers.list" class="permission-name add-link" data-text="speakerid.speakers.list" tabindex="-1"><code dir="ltr" translate="no">speakerid.speakers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.viewer">Speaker ID Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.verifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speakerid.speakers.verify" class="permission-name add-link" data-text="speakerid.speakers.verify" tabindex="-1"><code dir="ltr" translate="no">speakerid.speakers.verify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.admin">Speaker ID Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.editor">Speaker ID Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speakerid#speakerid.verifier">Speaker ID Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speakerid.verifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
