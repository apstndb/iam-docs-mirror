---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/agentregistry
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry
title: Agent Registry roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Agent Registry. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Agent Registry roles

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
<td><h4 id="agentregistry.admin" class="role-title add-link" data-text="Agent Registry API Admin Beta" tabindex="-1">Agent Registry API Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p>Full access to Agent Registry API resources.</p></td>
<td><p><code dir="ltr" translate="no">agentregistry.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.agents.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.search</code></li>
<li><code dir="ltr" translate="no">agentregistry.bindings.create</code></li>
<li><code dir="ltr" translate="no">agentregistry.bindings.delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.  bindings.  fetchAvailable</code></li>
<li><code dir="ltr" translate="no">agentregistry.bindings.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.bindings.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.bindings.update</code></li>
<li><code dir="ltr" translate="no">agentregistry.endpoints.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.endpoints.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.locations.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.  mcpServers.  search</code></li>
<li><code dir="ltr" translate="no">agentregistry.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">agentregistry.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.operations.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.operations.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.publishers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.publishers.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.create</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.update</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  create</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  get</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  list</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.create</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.search</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.editor" class="role-title add-link" data-text="Agent Registry API Editor Beta" tabindex="-1">Agent Registry API Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p>Edit access to Agent Registry API resources.</p></td>
<td><p><code dir="ltr" translate="no">agentregistry.agents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.agents.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.search</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.  bindings.  fetchAvailable</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.endpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.endpoints.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.endpoints.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.mcpServers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.  mcpServers.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">agentregistry.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.operations.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.publishers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.publishers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.publishers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.services.create</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.services.update</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.skillRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  create</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  get</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.skills.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.skills.create</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.search</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.viewer" class="role-title add-link" data-text="Agent Registry API Viewer Beta" tabindex="-1">Agent Registry API Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p>Readonly access to Agent Registry API resources.</p></td>
<td><p><code dir="ltr" translate="no">agentregistry.agents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.agents.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.search</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.  bindings.  fetchAvailable</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.endpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.endpoints.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.endpoints.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.mcpServers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.  mcpServers.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.operations.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.operations.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.publishers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.publishers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.publishers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.services.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.services.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.  skillRevisions.  get</code></p>
<p><code dir="ltr" translate="no">agentregistry.  skillRevisions.  list</code></p>
<p><code dir="ltr" translate="no">agentregistry.skills.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.skills.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.skills.search</code></p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.user" class="role-title add-link" data-text="Agent Registry User Beta" tabindex="-1">Agent Registry User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p>Create, update, and delete skills and skill revisions.</p></td>
<td><p><code dir="ltr" translate="no">agentregistry.agents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.agents.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.agents.search</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.  bindings.  fetchAvailable</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.endpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.endpoints.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.endpoints.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.mcpServers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.  mcpServers.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.operations.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.operations.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.publishers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.publishers.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.publishers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.services.get</code></p>
<p><code dir="ltr" translate="no">agentregistry.services.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.skillRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  create</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  get</code></li>
<li><code dir="ltr" translate="no">agentregistry.  skillRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.skills.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentregistry.skills.create</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.delete</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.get</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.list</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.search</code></li>
<li><code dir="ltr" translate="no">agentregistry.skills.update</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Agent Registry permissions

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
<td><h4 id="agentregistry.agents.get" class="permission-name add-link" data-text="agentregistry.agents.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.agents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.agents.list" class="permission-name add-link" data-text="agentregistry.agents.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.agents.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.agents.search" class="permission-name add-link" data-text="agentregistry.agents.search" tabindex="-1"><code dir="ltr" translate="no">agentregistry.agents.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.bindings.create" class="permission-name add-link" data-text="agentregistry.bindings.create" tabindex="-1"><code dir="ltr" translate="no">agentregistry.bindings.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.bindings.delete" class="permission-name add-link" data-text="agentregistry.bindings.delete" tabindex="-1"><code dir="ltr" translate="no">agentregistry.bindings.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.bindings.fetchAvailable" class="permission-name add-link" data-text="agentregistry.bindings.fetchAvailable" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  bindings.  fetchAvailable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.bindings.get" class="permission-name add-link" data-text="agentregistry.bindings.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.bindings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.bindings.list" class="permission-name add-link" data-text="agentregistry.bindings.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.bindings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.bindings.update" class="permission-name add-link" data-text="agentregistry.bindings.update" tabindex="-1"><code dir="ltr" translate="no">agentregistry.bindings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.endpoints.get" class="permission-name add-link" data-text="agentregistry.endpoints.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.endpoints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.endpoints.list" class="permission-name add-link" data-text="agentregistry.endpoints.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.endpoints.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.locations.get" class="permission-name add-link" data-text="agentregistry.locations.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.locations.list" class="permission-name add-link" data-text="agentregistry.locations.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.mcpServers.get" class="permission-name add-link" data-text="agentregistry.mcpServers.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.mcpServers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.mcpServers.list" class="permission-name add-link" data-text="agentregistry.mcpServers.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.mcpServers.search" class="permission-name add-link" data-text="agentregistry.mcpServers.search" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  mcpServers.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.operations.cancel" class="permission-name add-link" data-text="agentregistry.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.operations.delete" class="permission-name add-link" data-text="agentregistry.operations.delete" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.operations.get" class="permission-name add-link" data-text="agentregistry.operations.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.operations.list" class="permission-name add-link" data-text="agentregistry.operations.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.publishers.get" class="permission-name add-link" data-text="agentregistry.publishers.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.publishers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.publishers.list" class="permission-name add-link" data-text="agentregistry.publishers.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.publishers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.services.create" class="permission-name add-link" data-text="agentregistry.services.create" tabindex="-1"><code dir="ltr" translate="no">agentregistry.services.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.services.delete" class="permission-name add-link" data-text="agentregistry.services.delete" tabindex="-1"><code dir="ltr" translate="no">agentregistry.services.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.services.get" class="permission-name add-link" data-text="agentregistry.services.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.services.list" class="permission-name add-link" data-text="agentregistry.services.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.services.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.services.update" class="permission-name add-link" data-text="agentregistry.services.update" tabindex="-1"><code dir="ltr" translate="no">agentregistry.services.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.skillRevisions.create" class="permission-name add-link" data-text="agentregistry.skillRevisions.create" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  skillRevisions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.skillRevisions.delete" class="permission-name add-link" data-text="agentregistry.skillRevisions.delete" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  skillRevisions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.skillRevisions.get" class="permission-name add-link" data-text="agentregistry.skillRevisions.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  skillRevisions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.skillRevisions.list" class="permission-name add-link" data-text="agentregistry.skillRevisions.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.  skillRevisions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.skills.create" class="permission-name add-link" data-text="agentregistry.skills.create" tabindex="-1"><code dir="ltr" translate="no">agentregistry.skills.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.skills.delete" class="permission-name add-link" data-text="agentregistry.skills.delete" tabindex="-1"><code dir="ltr" translate="no">agentregistry.skills.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.skills.get" class="permission-name add-link" data-text="agentregistry.skills.get" tabindex="-1"><code dir="ltr" translate="no">agentregistry.skills.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.skills.list" class="permission-name add-link" data-text="agentregistry.skills.list" tabindex="-1"><code dir="ltr" translate="no">agentregistry.skills.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentregistry.skills.search" class="permission-name add-link" data-text="agentregistry.skills.search" tabindex="-1"><code dir="ltr" translate="no">agentregistry.skills.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.viewer">Agent Registry API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentregistry.skills.update" class="permission-name add-link" data-text="agentregistry.skills.update" tabindex="-1"><code dir="ltr" translate="no">agentregistry.skills.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.admin">Agent Registry API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.editor">Agent Registry API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentregistry#agentregistry.user">Agent Registry User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentregistry.user</code> )</p></td>
</tr>
</tbody>
</table>
