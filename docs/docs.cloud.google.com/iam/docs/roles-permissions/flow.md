---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/flow
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/flow
title: Flow roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Flow. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Flow roles

| Role                                                                                                                        | Permissions                                                    |
|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| Flow Admin <sup>Beta</sup> ( `roles/ flow.admin` ) Full access to all Flow resources. Intended for project administrators.  | `resourcemanager.projects.get` `resourcemanager.projects.list` |
| Flow Editor <sup>Beta</sup> ( `roles/ flow.editor` ) Create and manage Flow generated media. Intended for content creators. | `resourcemanager.projects.get` `resourcemanager.projects.list` |

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
<td>FlowService Service Agent
<p>( <code>roles/ aisandbox.serviceAgent</code> )</p>
<p>Grants FlowService Service Agent permissions to manage resources in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.predict</code></p>
<p><code>aiplatform.interactions.create</code></p>
<p><code>aiplatform.interactions.get</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>Flow Service Agent
<p>( <code>roles/ flow.serviceAgent</code> )</p>
<p>Grants Flow Service Agent permissions to manage resources in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.predict</code></p>
<p><code>aiplatform.interactions.create</code></p>
<p><code>aiplatform.interactions.get</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Flow permissions

There are no IAM permissions for this service.
