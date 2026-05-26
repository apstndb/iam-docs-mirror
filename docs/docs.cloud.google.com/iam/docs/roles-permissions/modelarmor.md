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
<td><h4 id="modelarmor.admin" class="role-title add-link" data-text="Model Armor Admin" tabindex="-1">Model Armor Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p>Grants full access to all modelarmor resources. Intended for administrators &amp; owners.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.templates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.templates.create</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.delete</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.list</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.update</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeInput</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeModelResponse</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeOutput</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeUserPrompt</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeModelResponse</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeUserPrompt</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.editor" class="role-title add-link" data-text="Model Armor Editor" tabindex="-1">Model Armor Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p>Editor role for Model Armor resources.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.callouts.invoke</code></p>
<p><code dir="ltr" translate="no">modelarmor.  floorSettings.  computeEffectiveFloorSetting</code></p>
<p><code dir="ltr" translate="no">modelarmor.floorSettings.get</code></p>
<p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.templates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.templates.create</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.delete</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.list</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.update</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeInput</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeModelResponse</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeOutput</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeUserPrompt</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeModelResponse</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeUserPrompt</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.viewer" class="role-title add-link" data-text="Model Armor Viewer" tabindex="-1">Model Armor Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p>Grants read access to all model armor resources. Intended for viewers.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.templates.get</code></p>
<p><code dir="ltr" translate="no">modelarmor.templates.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.calloutUser" class="role-title add-link" data-text="Model Armor Callout User Beta" tabindex="-1">Model Armor Callout User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.calloutUser</code> )</p>
<p>Grants access to use Model Armor Callout service. Intended for users &amp; applications which plan to use Model Armor Callout service.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.callouts.invoke</code></p>
<p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.floorSettingsAdmin" class="role-title add-link" data-text="Model Armor Floor Setting Admin" tabindex="-1">Model Armor Floor Setting Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p>Grants full access to all Model Armor Floor Setting resources. Intended for administrators &amp; owners.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.floorSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.  floorSettings.  computeEffectiveFloorSetting</code></li>
<li><code dir="ltr" translate="no">modelarmor.floorSettings.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.  floorSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.floorSettingsViewer" class="role-title add-link" data-text="Model Armor Floor Setting Viewer" tabindex="-1">Model Armor Floor Setting Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p>Grants read access to all Model Armor Floor Setting resources. Intended for viewers.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.floorSettings.get</code></p>
<p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.user" class="role-title add-link" data-text="Model Armor User" tabindex="-1">Model Armor User</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Grants access to sanitize APIs for templates. Intended for users &amp; applications which plan to use a template.</p></td>
<td><p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeInput</code></p>
<p><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeModelResponse</code></p>
<p><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeOutput</code></p>
<p><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeUserPrompt</code></p>
<p><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeModelResponse</code></p>
<p><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeUserPrompt</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="modelarmor.serviceAgent" class="role-title add-link" data-text="Model Armor Service Agent" tabindex="-1">Model Armor Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</p>
<p>Gives Model Armor Service Account permission to make DLP calls.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.list</code></p>
<p><code dir="ltr" translate="no">dlp.kms.encrypt</code></p>
<p><code dir="ltr" translate="no">dlp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.locations.get</code></li>
<li><code dir="ltr" translate="no">dlp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></p>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
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
<td><h4 id="modelarmor.callouts.invoke" class="permission-name add-link" data-text="modelarmor.callouts.invoke" tabindex="-1"><code dir="ltr" translate="no">modelarmor.callouts.invoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.calloutUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.floorSettings.computeEffectiveFloorSetting" class="permission-name add-link" data-text="modelarmor.floorSettings.computeEffectiveFloorSetting" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  floorSettings.  computeEffectiveFloorSetting</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.floorSettings.get" class="permission-name add-link" data-text="modelarmor.floorSettings.get" tabindex="-1"><code dir="ltr" translate="no">modelarmor.floorSettings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.floorSettings.update" class="permission-name add-link" data-text="modelarmor.floorSettings.update" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  floorSettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.locations.get" class="permission-name add-link" data-text="modelarmor.locations.get" tabindex="-1"><code dir="ltr" translate="no">modelarmor.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.locations.list" class="permission-name add-link" data-text="modelarmor.locations.list" tabindex="-1"><code dir="ltr" translate="no">modelarmor.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.templates.create" class="permission-name add-link" data-text="modelarmor.templates.create" tabindex="-1"><code dir="ltr" translate="no">modelarmor.templates.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.templates.delete" class="permission-name add-link" data-text="modelarmor.templates.delete" tabindex="-1"><code dir="ltr" translate="no">modelarmor.templates.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.templates.get" class="permission-name add-link" data-text="modelarmor.templates.get" tabindex="-1"><code dir="ltr" translate="no">modelarmor.templates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.templates.list" class="permission-name add-link" data-text="modelarmor.templates.list" tabindex="-1"><code dir="ltr" translate="no">modelarmor.templates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.templates.update" class="permission-name add-link" data-text="modelarmor.templates.update" tabindex="-1"><code dir="ltr" translate="no">modelarmor.templates.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.templates.useToSanitizeInput" class="permission-name add-link" data-text="modelarmor.templates.useToSanitizeInput" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeInput</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.templates.useToSanitizeModelResponse" class="permission-name add-link" data-text="modelarmor.templates.useToSanitizeModelResponse" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeModelResponse</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.templates.useToSanitizeOutput" class="permission-name add-link" data-text="modelarmor.templates.useToSanitizeOutput" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeOutput</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.templates.useToSanitizeUserPrompt" class="permission-name add-link" data-text="modelarmor.templates.useToSanitizeUserPrompt" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeUserPrompt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="modelarmor.templates.useToStreamSanitizeModelResponse" class="permission-name add-link" data-text="modelarmor.templates.useToStreamSanitizeModelResponse" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeModelResponse</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="modelarmor.templates.useToStreamSanitizeUserPrompt" class="permission-name add-link" data-text="modelarmor.templates.useToStreamSanitizeUserPrompt" tabindex="-1"><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeUserPrompt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p></td>
</tr>
</tbody>
</table>
