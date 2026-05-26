---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/mcp
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/mcp
title: Google Cloud MCP servers roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud MCP servers. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud MCP servers roles

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
<td><h4 id="mcp.admin" class="role-title add-link" data-text="MCP Admin" tabindex="-1">MCP Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  mcp.admin</code> )</p>
<p>Full access for interacting with Google-managed MCP servers.</p></td>
<td><p><code dir="ltr" translate="no">mcp.tools.call</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="mcp.toolUser" class="role-title add-link" data-text="MCP Tool User" tabindex="-1">MCP Tool User</h4>
<p>( <code dir="ltr" translate="no">roles/  mcp.toolUser</code> )</p>
<p>Gives permission to call tools on any MCP server enabled by the parent project.</p></td>
<td><p><code dir="ltr" translate="no">mcp.tools.call</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud MCP servers permissions

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
<td><h4 id="mcp.tools.call" class="permission-name add-link" data-text="mcp.tools.call" tabindex="-1"><code dir="ltr" translate="no">mcp.tools.call</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.admin">MCP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mcp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser">MCP Tool User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mcp.toolUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
