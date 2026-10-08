---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/telemetry
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry
title: Telemetry API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Telemetry API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Telemetry API roles

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
<td>Telemetry Admin
<p>( <code>roles/ telemetry.admin</code> )</p>
<p>Admin role for telemetry</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>telemetry.*</code></p>
<ul>
<li><code>telemetry. consumers. getIamPolicy</code></li>
<li><code>telemetry. consumers. setIamPolicy</code></li>
<li><code>telemetry.consumers.writeLogs</code></li>
<li><code>telemetry. consumers. writeMetrics</code></li>
<li><code>telemetry. consumers. writeTraces</code></li>
<li><code>telemetry.traces.write</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Telemetry Editor
<p>( <code>roles/ telemetry.editor</code> )</p>
<p>Editor role for telemetry</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>telemetry.traces.write</code></p></td>
</tr>
<tr class="odd">
<td>Consumer Admin <sup>Beta</sup>
<p>( <code>roles/ telemetry.consumerAdmin</code> )</p>
<p>Grants permission management access to consumer resources.</p></td>
<td><p><code>telemetry. consumers. getIamPolicy</code></p>
<p><code>telemetry. consumers. setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td>Cloud Telemetry Logs Writer
<p>( <code>roles/ telemetry.logsWriter</code> )</p>
<p>Access to write logs.</p></td>
<td><p><code>logging.logEntries.create</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Telemetry Metrics Writer
<p>( <code>roles/ telemetry.metricsWriter</code> )</p>
<p>Access to write metrics.</p></td>
<td><p><code>monitoring.timeSeries.create</code></p></td>
</tr>
<tr class="even">
<td>Integrated Service Telemetry Logs Writer <sup>Beta</sup>
<p>( <code>roles/ telemetry.serviceLogsWriter</code> )</p>
<p>Allows an onboarded service to write log data to a destination.</p></td>
<td><p><code>telemetry.consumers.writeLogs</code></p></td>
</tr>
<tr class="odd">
<td>Integrated Service Telemetry Metrics Writer <sup>Beta</sup>
<p>( <code>roles/ telemetry.serviceMetricsWriter</code> )</p>
<p>Allows an onboarded service to write metrics data to a destination.</p></td>
<td><p><code>telemetry. consumers. writeMetrics</code></p></td>
</tr>
<tr class="even">
<td>Integrated Service Telemetry Writer <sup>Beta</sup>
<p>( <code>roles/ telemetry.serviceTelemetryWriter</code> )</p>
<p>Allows an onboarded service to write all telemetry data to a destination.</p></td>
<td><p><code>telemetry.consumers.writeLogs</code></p>
<p><code>telemetry. consumers. writeMetrics</code></p>
<p><code>telemetry. consumers. writeTraces</code></p></td>
</tr>
<tr class="odd">
<td>Integrated Service Telemetry Traces Writer <sup>Beta</sup>
<p>( <code>roles/ telemetry.serviceTracesWriter</code> )</p>
<p>Allows an onboarded service to write trace data to a destination.</p></td>
<td><p><code>telemetry. consumers. writeTraces</code></p></td>
</tr>
<tr class="even">
<td>Cloud Telemetry Traces Writer
<p>( <code>roles/ telemetry.tracesWriter</code> )</p>
<p>Access to write trace spans.</p></td>
<td><p><code>telemetry.traces.write</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Telemetry Writer
<p>( <code>roles/ telemetry.writer</code> )</p>
<p>Full access to write all telemetry data.</p></td>
<td><p><code>logging.logEntries.create</code></p>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>telemetry.traces.write</code></p></td>
</tr>
</tbody>
</table>

## Telemetry API permissions

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
<td><code>telemetry. consumers. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.consumerAdmin">Consumer Admin</a> ( <code>roles/ telemetry.consumerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>telemetry. consumers. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.consumerAdmin">Consumer Admin</a> ( <code>roles/ telemetry.consumerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>telemetry.consumers.writeLogs</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceLogsWriter">Integrated Service Telemetry Logs Writer</a> ( <code>roles/ telemetry.serviceLogsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTelemetryWriter">Integrated Service Telemetry Writer</a> ( <code>roles/ telemetry.serviceTelemetryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><code>telemetry. consumers. writeMetrics</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceMetricsWriter">Integrated Service Telemetry Metrics Writer</a> ( <code>roles/ telemetry.serviceMetricsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTelemetryWriter">Integrated Service Telemetry Writer</a> ( <code>roles/ telemetry.serviceTelemetryWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><code>telemetry. consumers. writeTraces</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTelemetryWriter">Integrated Service Telemetry Writer</a> ( <code>roles/ telemetry.serviceTelemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTracesWriter">Integrated Service Telemetry Traces Writer</a> ( <code>roles/ telemetry.serviceTracesWriter</code> )</p></td>
</tr>
<tr class="even">
<td><code>telemetry.traces.write</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.editor">Telemetry Editor</a> ( <code>roles/ telemetry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.agent">Cloud Trace Agent</a> ( <code>roles/ cloudtrace.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.tracesWriter">Cloud Telemetry Traces Writer</a> ( <code>roles/ telemetry.tracesWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.writer">Cloud Telemetry Writer</a> ( <code>roles/ telemetry.writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase AI Logic Service Agent</a> ( <code>roles/ firebaseml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
