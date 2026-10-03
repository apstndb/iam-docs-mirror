---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigquerycontinuousquery
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerycontinuousquery
title: BigQuery Continuous Query roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Continuous Query. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Continuous Query roles

BigQuery Continuous Query offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>BigQuery Continuous Query Service Agent
<p>( <code>roles/ bigquerycontinuousquery.serviceAgent</code> )</p>
<p>Gives BigQuery Continuous Query access to the service accounts in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>iam. serviceAccounts. getAccessToken</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Continuous Query permissions

There are no IAM permissions for this service.
