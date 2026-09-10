---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigqueryomni
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryomni
title: BigQuery Omni roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Omni. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Omni roles

BigQuery Omni offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="bigqueryomni.serviceAgent" class="role-title add-link" data-text="BigQuery Omni Service Agent" tabindex="-1">BigQuery Omni Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  bigqueryomni.serviceAgent</code> )</p>
<p>Gives BigQuery Omni access to tables in user projects.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Omni permissions

There are no IAM permissions for this service.
