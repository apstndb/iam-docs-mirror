---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry
title: Firebase Telemetry roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Telemetry. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Telemetry roles

Firebase Telemetry offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Firebase Telemetry Service Agent
<p>( <code>roles/ firebasetelemetry.serviceAgent</code> )</p>
<p>Access to Cloud Storage, Cloud Monitoring, and Cloud Logging for Firebase Telemetry.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudtrace.traces.patch</code></p>
<p><code>logging.buckets.create</code></p>
<p><code>logging.buckets.get</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging.buckets.update</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>logging.sinks.*</code></p>
<ul>
<li><code>logging.sinks.create</code></li>
<li><code>logging.sinks.delete</code></li>
<li><code>logging.sinks.get</code></li>
<li><code>logging.sinks.list</code></li>
<li><code>logging.sinks.update</code></li>
</ul>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.get</code></p>
<p><code>telemetry.traces.write</code></p></td>
</tr>
</tbody>
</table>

## Firebase Telemetry permissions

There are no IAM permissions for this service.
