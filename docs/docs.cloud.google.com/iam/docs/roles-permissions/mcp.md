---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/mcp
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/mcp
title: Google Cloud MCP servers roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud MCP servers. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud MCP servers roles

| Role                                                                                                                    | Permissions                                                                     |
|-------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| MCP Admin ( `roles/ mcp.admin` ) Full access for interacting with Google-managed MCP servers.                           | `mcp.tools.call` `resourcemanager.projects.get` `resourcemanager.projects.list` |
| MCP Tool User ( `roles/ mcp.toolUser` ) Gives permission to call tools on any MCP server enabled by the parent project. | `mcp.tools.call` `resourcemanager.projects.get` `resourcemanager.projects.list` |

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
<td><code>mcp.tools.call</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.admin">MCP Admin</a> ( <code>roles/ mcp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser">MCP Tool User</a> ( <code>roles/ mcp.toolUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
