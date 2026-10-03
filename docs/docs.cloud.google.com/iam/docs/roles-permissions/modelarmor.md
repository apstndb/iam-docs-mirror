---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/modelarmor
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor
title: Model Armor roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Model Armor. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Model Armor roles

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
<td>Model Armor Admin
<p>( <code>roles/ modelarmor.admin</code> )</p>
<p>Grants full access to all modelarmor resources. Intended for administrators &amp; owners.</p></td>
<td><p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>modelarmor.templates.*</code></p>
<ul>
<li><code>modelarmor.templates.create</code></li>
<li><code>modelarmor.templates.delete</code></li>
<li><code>modelarmor.templates.get</code></li>
<li><code>modelarmor.templates.list</code></li>
<li><code>modelarmor.templates.update</code></li>
<li><code>modelarmor. templates. useToSanitizeInput</code></li>
<li><code>modelarmor. templates. useToSanitizeModelResponse</code></li>
<li><code>modelarmor. templates. useToSanitizeOutput</code></li>
<li><code>modelarmor. templates. useToSanitizeUserPrompt</code></li>
<li><code>modelarmor. templates. useToStreamSanitizeModelResponse</code></li>
<li><code>modelarmor. templates. useToStreamSanitizeUserPrompt</code></li>
</ul>
<p><code>modelarmor.topics.*</code></p>
<ul>
<li><code>modelarmor.topics.create</code></li>
<li><code>modelarmor.topics.delete</code></li>
<li><code>modelarmor.topics.get</code></li>
<li><code>modelarmor.topics.list</code></li>
<li><code>modelarmor.topics.test</code></li>
<li><code>modelarmor.topics.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Model Armor Editor
<p>( <code>roles/ modelarmor.editor</code> )</p>
<p>Grants access to create and update all model armor resources. Intended for editors.</p></td>
<td><p><code>modelarmor.callouts.invoke</code></p>
<p><code>modelarmor. floorSettings. computeEffectiveFloorSetting</code></p>
<p><code>modelarmor.floorSettings.get</code></p>
<p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>modelarmor.templates.*</code></p>
<ul>
<li><code>modelarmor.templates.create</code></li>
<li><code>modelarmor.templates.delete</code></li>
<li><code>modelarmor.templates.get</code></li>
<li><code>modelarmor.templates.list</code></li>
<li><code>modelarmor.templates.update</code></li>
<li><code>modelarmor. templates. useToSanitizeInput</code></li>
<li><code>modelarmor. templates. useToSanitizeModelResponse</code></li>
<li><code>modelarmor. templates. useToSanitizeOutput</code></li>
<li><code>modelarmor. templates. useToSanitizeUserPrompt</code></li>
<li><code>modelarmor. templates. useToStreamSanitizeModelResponse</code></li>
<li><code>modelarmor. templates. useToStreamSanitizeUserPrompt</code></li>
</ul>
<p><code>modelarmor.topics.*</code></p>
<ul>
<li><code>modelarmor.topics.create</code></li>
<li><code>modelarmor.topics.delete</code></li>
<li><code>modelarmor.topics.get</code></li>
<li><code>modelarmor.topics.list</code></li>
<li><code>modelarmor.topics.test</code></li>
<li><code>modelarmor.topics.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Model Armor Viewer
<p>( <code>roles/ modelarmor.viewer</code> )</p>
<p>Grants read access to all model armor resources. Intended for viewers.</p></td>
<td><p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>modelarmor.templates.get</code></p>
<p><code>modelarmor.templates.list</code></p>
<p><code>modelarmor.topics.get</code></p>
<p><code>modelarmor.topics.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Model Armor Callout User <sup>Beta</sup>
<p>( <code>roles/ modelarmor.calloutUser</code> )</p>
<p>Grants access to use Model Armor Callout service. Intended for users &amp; applications which plan to use Model Armor Callout service.</p></td>
<td><p><code>modelarmor.callouts.invoke</code></p>
<p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Model Armor Floor Setting Admin
<p>( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p>Grants full access to all Model Armor Floor Setting resources. Intended for administrators &amp; owners.</p></td>
<td><p><code>modelarmor.floorSettings.*</code></p>
<ul>
<li><code>modelarmor. floorSettings. computeEffectiveFloorSetting</code></li>
<li><code>modelarmor.floorSettings.get</code></li>
<li><code>modelarmor. floorSettings. update</code></li>
</ul>
<p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Model Armor Floor Setting Viewer
<p>( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p>Grants read access to all Model Armor Floor Setting resources. Intended for viewers.</p></td>
<td><p><code>modelarmor.floorSettings.get</code></p>
<p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Model Armor User
<p>( <code>roles/ modelarmor.user</code> )</p>
<p>Grants access to sanitize APIs for templates and to use and test topics. Intended for users &amp; applications which plan to use a template or topic for sanitization.</p></td>
<td><p><code>modelarmor.locations.*</code></p>
<ul>
<li><code>modelarmor.locations.get</code></li>
<li><code>modelarmor.locations.list</code></li>
</ul>
<p><code>modelarmor. templates. useToSanitizeInput</code></p>
<p><code>modelarmor. templates. useToSanitizeModelResponse</code></p>
<p><code>modelarmor. templates. useToSanitizeOutput</code></p>
<p><code>modelarmor. templates. useToSanitizeUserPrompt</code></p>
<p><code>modelarmor. templates. useToStreamSanitizeModelResponse</code></p>
<p><code>modelarmor. templates. useToStreamSanitizeUserPrompt</code></p>
<p><code>modelarmor.topics.test</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Model Armor Service Agent
<p>( <code>roles/ modelarmor.serviceAgent</code> )</p>
<p>Gives Model Armor Service Account permission to make DLP calls.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>dlp.analyzeRiskTemplates.get</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p>
<p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.inspectFindings.list</code></p>
<p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.get</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.jobs.get</code></p>
<p><code>dlp.jobs.list</code></p>
<p><code>dlp.kms.encrypt</code></p>
<p><code>dlp.locations.*</code></p>
<ul>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
</ul>
<p><code>dlp.storedInfoTypes.get</code></p>
<p><code>dlp.storedInfoTypes.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Model Armor permissions

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
<td><code>modelarmor.callouts.invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code>roles/ modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>modelarmor. floorSettings. computeEffectiveFloorSetting</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.floorSettings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor. floorSettings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code>roles/ modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>modelarmor.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code>roles/ modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>modelarmor.templates.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor.templates.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.templates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor.templates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.templates.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor. templates. useToSanitizeInput</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>modelarmor. templates. useToSanitizeModelResponse</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>modelarmor. templates. useToSanitizeOutput</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>modelarmor. templates. useToSanitizeUserPrompt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>modelarmor. templates. useToStreamSanitizeModelResponse</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor. templates. useToStreamSanitizeUserPrompt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor.topics.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.topics.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor.topics.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.topics.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>modelarmor.topics.test</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>modelarmor.topics.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
