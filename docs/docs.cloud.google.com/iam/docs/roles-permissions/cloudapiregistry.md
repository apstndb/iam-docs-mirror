---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry
title: Cloud API Registry roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud API Registry. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud API Registry roles

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
<td><h4 id="cloudapiregistry.admin" class="role-title add-link" data-text="Cloud API Registry Admin Beta" tabindex="-1">Cloud API Registry Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p>Read/write access to Cloud API Registry resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudapiregistry.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudapiregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.  locations.  list</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  get</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  list</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.mcpTools.get</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.mcpTools.list</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivemcppolicy.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudapiregistry.viewer" class="role-title add-link" data-text="Cloud API Registry Viewer Beta" tabindex="-1">Cloud API Registry Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p>Read-only access to Cloud API Registry resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudapiregistry.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudapiregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.  locations.  list</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  get</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  list</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.mcpTools.get</code></li>
<li><code dir="ltr" translate="no">cloudapiregistry.mcpTools.list</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivemcppolicy.  get</code></p></td>
</tr>
</tbody>
</table>

## Cloud API Registry permissions

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
<td><h4 id="cloudapiregistry.locations.get" class="permission-name add-link" data-text="cloudapiregistry.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloudapiregistry.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudapiregistry.locations.list" class="permission-name add-link" data-text="cloudapiregistry.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudapiregistry.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudapiregistry.mcpServers.get" class="permission-name add-link" data-text="cloudapiregistry.mcpServers.get" tabindex="-1"><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudapiregistry.mcpServers.list" class="permission-name add-link" data-text="cloudapiregistry.mcpServers.list" tabindex="-1"><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudapiregistry.mcpTools.get" class="permission-name add-link" data-text="cloudapiregistry.mcpTools.get" tabindex="-1"><code dir="ltr" translate="no">cloudapiregistry.mcpTools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudapiregistry.mcpTools.list" class="permission-name add-link" data-text="cloudapiregistry.mcpTools.list" tabindex="-1"><code dir="ltr" translate="no">cloudapiregistry.mcpTools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
