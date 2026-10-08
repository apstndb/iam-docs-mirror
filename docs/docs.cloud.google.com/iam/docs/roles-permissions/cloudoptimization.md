---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization
title: Cloud Optimization roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Optimization. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Optimization roles

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
<td>Cloud Optimization AI Admin
<p>( <code>roles/ cloudoptimization.admin</code> )</p>
<p>Administrator of Cloud Optimization AI resources</p></td>
<td><p><code>cloudoptimization.*</code></p>
<ul>
<li><code>cloudoptimization. operations. create</code></li>
<li><code>cloudoptimization. operations. get</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Optimization AI Editor
<p>( <code>roles/ cloudoptimization.editor</code> )</p>
<p>Editor of Cloud Optimization AI resources</p></td>
<td><p><code>cloudoptimization.*</code></p>
<ul>
<li><code>cloudoptimization. operations. create</code></li>
<li><code>cloudoptimization. operations. get</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Optimization AI Viewer
<p>( <code>roles/ cloudoptimization.viewer</code> )</p>
<p>Viewer of Cloud Optimization AI resources</p></td>
<td><p><code>cloudoptimization. operations. get</code></p></td>
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
<td>Cloud Optimization Service Agent
<p>( <code>roles/ cloudoptimization.serviceAgent</code> )</p>
<p>Grants Cloud Optimization Service Account access to read and write data in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Cloud Optimization permissions

| Permission                              | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `cloudoptimization. operations. create` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Optimization AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.admin) ( `roles/ cloudoptimization.admin` ) [Cloud Optimization AI Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.editor) ( `roles/ cloudoptimization.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `cloudoptimization. operations. get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Optimization AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.admin) ( `roles/ cloudoptimization.admin` ) [Cloud Optimization AI Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.editor) ( `roles/ cloudoptimization.editor` ) [Cloud Optimization AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.viewer) ( `roles/ cloudoptimization.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
