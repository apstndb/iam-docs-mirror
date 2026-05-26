---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/speech
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/speech
title: Speech-to-Text roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Speech-to-Text. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Speech-to-Text roles

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
<td><h4 id="speech.admin" class="role-title add-link" data-text="Cloud Speech Administrator" tabindex="-1">Cloud Speech Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p>Grants full access to all resources in Speech-to-text</p></td>
<td><p><code dir="ltr" translate="no">speech.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.adaptations.execute</code></li>
<li><code dir="ltr" translate="no">speech.config.get</code></li>
<li><code dir="ltr" translate="no">speech.config.update</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.create</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.delete</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.get</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.list</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.undelete</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.update</code></li>
<li><code dir="ltr" translate="no">speech.locations.get</code></li>
<li><code dir="ltr" translate="no">speech.locations.list</code></li>
<li><code dir="ltr" translate="no">speech.operations.cancel</code></li>
<li><code dir="ltr" translate="no">speech.operations.delete</code></li>
<li><code dir="ltr" translate="no">speech.operations.get</code></li>
<li><code dir="ltr" translate="no">speech.operations.list</code></li>
<li><code dir="ltr" translate="no">speech.operations.wait</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.create</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.delete</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.get</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.list</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.undelete</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.update</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.create</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.delete</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.get</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.list</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.recognize</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.undelete</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.editor" class="role-title add-link" data-text="Cloud Speech Editor" tabindex="-1">Cloud Speech Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p>Grants access to edit resources in Speech-to-text</p></td>
<td><p><code dir="ltr" translate="no">speech.adaptations.execute</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.customClasses.create</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.delete</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.get</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.list</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.undelete</code></li>
<li><code dir="ltr" translate="no">speech.customClasses.update</code></li>
</ul>
<p><code dir="ltr" translate="no">speech.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.locations.get</code></li>
<li><code dir="ltr" translate="no">speech.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">speech.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.operations.cancel</code></li>
<li><code dir="ltr" translate="no">speech.operations.delete</code></li>
<li><code dir="ltr" translate="no">speech.operations.get</code></li>
<li><code dir="ltr" translate="no">speech.operations.list</code></li>
<li><code dir="ltr" translate="no">speech.operations.wait</code></li>
</ul>
<p><code dir="ltr" translate="no">speech.phraseSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.phraseSets.create</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.delete</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.get</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.list</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.undelete</code></li>
<li><code dir="ltr" translate="no">speech.phraseSets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">speech.recognizers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.recognizers.create</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.delete</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.get</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.list</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.recognize</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.undelete</code></li>
<li><code dir="ltr" translate="no">speech.recognizers.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speech.client" class="role-title add-link" data-text="Cloud Speech Client" tabindex="-1">Cloud Speech Client</h4>
<p>( <code dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Grants access to the recognition APIs.</p></td>
<td><p><code dir="ltr" translate="no">speech.adaptations.execute</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.get</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.list</code></p>
<p><code dir="ltr" translate="no">speech.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">speech.locations.get</code></li>
<li><code dir="ltr" translate="no">speech.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">speech.operations.get</code></p>
<p><code dir="ltr" translate="no">speech.operations.list</code></p>
<p><code dir="ltr" translate="no">speech.operations.wait</code></p>
<p><code dir="ltr" translate="no">speech.phraseSets.get</code></p>
<p><code dir="ltr" translate="no">speech.phraseSets.list</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.get</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.list</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.recognize</code></p></td>
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
<td><h4 id="speech.serviceAgent" class="role-title add-link" data-text="Cloud Speech-to-Text Service Agent" tabindex="-1">Cloud Speech-to-Text Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  speech.serviceAgent</code> )</p>
<p>Gives Speech-to-Text service account access to Cloud Storage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Speech-to-Text permissions

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
<td><h4 id="speech.adaptations.execute" class="permission-name add-link" data-text="speech.adaptations.execute" tabindex="-1"><code dir="ltr" translate="no">speech.adaptations.execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.config.get" class="permission-name add-link" data-text="speech.config.get" tabindex="-1"><code dir="ltr" translate="no">speech.config.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.config.update" class="permission-name add-link" data-text="speech.config.update" tabindex="-1"><code dir="ltr" translate="no">speech.config.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.customClasses.create" class="permission-name add-link" data-text="speech.customClasses.create" tabindex="-1"><code dir="ltr" translate="no">speech.customClasses.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.customClasses.delete" class="permission-name add-link" data-text="speech.customClasses.delete" tabindex="-1"><code dir="ltr" translate="no">speech.customClasses.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.customClasses.get" class="permission-name add-link" data-text="speech.customClasses.get" tabindex="-1"><code dir="ltr" translate="no">speech.customClasses.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speech.customClasses.list" class="permission-name add-link" data-text="speech.customClasses.list" tabindex="-1"><code dir="ltr" translate="no">speech.customClasses.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.customClasses.undelete" class="permission-name add-link" data-text="speech.customClasses.undelete" tabindex="-1"><code dir="ltr" translate="no">speech.customClasses.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.customClasses.update" class="permission-name add-link" data-text="speech.customClasses.update" tabindex="-1"><code dir="ltr" translate="no">speech.customClasses.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.locations.get" class="permission-name add-link" data-text="speech.locations.get" tabindex="-1"><code dir="ltr" translate="no">speech.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.locations.list" class="permission-name add-link" data-text="speech.locations.list" tabindex="-1"><code dir="ltr" translate="no">speech.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.operations.cancel" class="permission-name add-link" data-text="speech.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">speech.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.operations.delete" class="permission-name add-link" data-text="speech.operations.delete" tabindex="-1"><code dir="ltr" translate="no">speech.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.operations.get" class="permission-name add-link" data-text="speech.operations.get" tabindex="-1"><code dir="ltr" translate="no">speech.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speech.operations.list" class="permission-name add-link" data-text="speech.operations.list" tabindex="-1"><code dir="ltr" translate="no">speech.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.operations.wait" class="permission-name add-link" data-text="speech.operations.wait" tabindex="-1"><code dir="ltr" translate="no">speech.operations.wait</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.phraseSets.create" class="permission-name add-link" data-text="speech.phraseSets.create" tabindex="-1"><code dir="ltr" translate="no">speech.phraseSets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.phraseSets.delete" class="permission-name add-link" data-text="speech.phraseSets.delete" tabindex="-1"><code dir="ltr" translate="no">speech.phraseSets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.phraseSets.get" class="permission-name add-link" data-text="speech.phraseSets.get" tabindex="-1"><code dir="ltr" translate="no">speech.phraseSets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.phraseSets.list" class="permission-name add-link" data-text="speech.phraseSets.list" tabindex="-1"><code dir="ltr" translate="no">speech.phraseSets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speech.phraseSets.undelete" class="permission-name add-link" data-text="speech.phraseSets.undelete" tabindex="-1"><code dir="ltr" translate="no">speech.phraseSets.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="speech.phraseSets.update" class="permission-name add-link" data-text="speech.phraseSets.update" tabindex="-1"><code dir="ltr" translate="no">speech.phraseSets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.recognizers.create" class="permission-name add-link" data-text="speech.recognizers.create" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.recognizers.delete" class="permission-name add-link" data-text="speech.recognizers.delete" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.recognizers.get" class="permission-name add-link" data-text="speech.recognizers.get" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.recognizers.list" class="permission-name add-link" data-text="speech.recognizers.list" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="speech.recognizers.recognize" class="permission-name add-link" data-text="speech.recognizers.recognize" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.recognize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.client">Cloud Speech Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="speech.recognizers.undelete" class="permission-name add-link" data-text="speech.recognizers.undelete" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech.recognizers.update" class="permission-name add-link" data-text="speech.recognizers.update" tabindex="-1"><code dir="ltr" translate="no">speech.recognizers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.admin">Cloud Speech Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.editor">Cloud Speech Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  speech.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
