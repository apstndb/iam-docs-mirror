---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/aisandbox
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/aisandbox
title: Flow roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Flow. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Flow roles

Flow offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="aisandbox.serviceAgent" class="role-title add-link" data-text="FlowService Service Agent" tabindex="-1">FlowService Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  aisandbox.serviceAgent</code> )</p>
<p>Grants FlowService Service Agent permissions to manage resources in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.endpoints.predict</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Flow permissions

There are no IAM permissions for this service.
