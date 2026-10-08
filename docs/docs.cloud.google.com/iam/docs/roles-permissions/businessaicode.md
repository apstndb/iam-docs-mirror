---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/businessaicode
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode
title: Business AI Code roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Business AI Code. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Business AI Code roles

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
<td>User role for Business AI Code API
<p>( <code>roles/ businessaicode.user</code> )</p>
<p>A user who can use Business AI Code API</p></td>
<td><p><code>businessaicode.*</code></p>
<ul>
<li><code>businessaicode. locations. fetchQuotaStatus</code></li>
<li><code>businessaicode. locations. generateContent</code></li>
<li><code>businessaicode. locations. queryConfiguration</code></li>
<li><code>businessaicode. locations. selfAssignLicense</code></li>
<li><code>businessaicode. locations. sendTelemetry</code></li>
</ul>
<p><code>cloudaicompanion. instances. exportMetrics</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSettingBindings</code></p>
<p><code>cloudaicompanion. licenses. selfAssign</code></p></td>
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
<td>Business AI Code Service Agent
<p>( <code>roles/ businessaicode.serviceAgent</code> )</p>
<p>Gives Business AI Code Assist the permissions to call Vertex and Discovery Engine Settings API.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.predict</code></p>
<p><code>discoveryengine. devToolsConfigs. get</code></p>
<p><code>discoveryengine. projectOverageConfigs. get</code></p>
<p><code>discoveryengine.projects.get</code></p>
<p><code>monitoring.timeSeries.list</code></p></td>
</tr>
</tbody>
</table>

## Business AI Code permissions

| Permission                                      | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `businessaicode. locations. fetchQuotaStatus`   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Discovery Engine User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user) ( `roles/ discoveryengine.user` ) [User role for Business AI Code API](https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user) ( `roles/ businessaicode.user` ) [Gemini Enterprise User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser) ( `roles/ discoveryengine.agentspaceUser` ) [Podcast API User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser) ( `roles/ discoveryengine.podcastApiUser` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `businessaicode. locations. generateContent`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Discovery Engine User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user) ( `roles/ discoveryengine.user` ) [User role for Business AI Code API](https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user) ( `roles/ businessaicode.user` ) [Gemini Enterprise User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser) ( `roles/ discoveryengine.agentspaceUser` ) [Podcast API User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser) ( `roles/ discoveryengine.podcastApiUser` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `businessaicode. locations. queryConfiguration` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Discovery Engine User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user) ( `roles/ discoveryengine.user` ) [User role for Business AI Code API](https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user) ( `roles/ businessaicode.user` ) [Gemini Enterprise User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser) ( `roles/ discoveryengine.agentspaceUser` ) [Podcast API User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser) ( `roles/ discoveryengine.podcastApiUser` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `businessaicode. locations. selfAssignLicense`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Discovery Engine User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user) ( `roles/ discoveryengine.user` ) [User role for Business AI Code API](https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user) ( `roles/ businessaicode.user` ) [Gemini Enterprise User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser) ( `roles/ discoveryengine.agentspaceUser` ) [Podcast API User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser) ( `roles/ discoveryengine.podcastApiUser` )                                                                                                                                                                                                                                                                                                                        |
| `businessaicode. locations. sendTelemetry`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Discovery Engine User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user) ( `roles/ discoveryengine.user` ) [User role for Business AI Code API](https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user) ( `roles/ businessaicode.user` ) [Gemini Enterprise User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser) ( `roles/ discoveryengine.agentspaceUser` ) [Podcast API User](https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser) ( `roles/ discoveryengine.podcastApiUser` )                                                                                                                                                                                                                                                                                                                        |
