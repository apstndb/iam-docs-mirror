---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection
title: BigQuery Connection API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Connection API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Connection API roles

BigQuery Connection API offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>BigQuery Connection Service Agent
<p>( <code>roles/ bigqueryconnection.serviceAgent</code> )</p>
<p>Gives BigQuery Connection Service access to Cloud SQL instances in user projects.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudsql.instances.connect</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Connection API permissions

There are no IAM permissions for this service.
