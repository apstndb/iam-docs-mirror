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
<td><h4 id="telemetry.admin" class="role-title add-link" data-text="Telemetry Admin" tabindex="-1">Telemetry Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p>Admin role for telemetry</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">telemetry.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telemetry.  consumers.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">telemetry.  consumers.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">telemetry.consumers.writeLogs</code></li>
<li><code dir="ltr" translate="no">telemetry.  consumers.  writeMetrics</code></li>
<li><code dir="ltr" translate="no">telemetry.  consumers.  writeTraces</code></li>
<li><code dir="ltr" translate="no">telemetry.traces.write</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.editor" class="role-title add-link" data-text="Telemetry Editor" tabindex="-1">Telemetry Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.editor</code> )</p>
<p>Editor role for telemetry</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">telemetry.traces.write</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.consumerAdmin" class="role-title add-link" data-text="Consumer Admin Beta" tabindex="-1">Consumer Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.consumerAdmin</code> )</p>
<p>Grants permission management access to consumer resources.</p></td>
<td><p><code dir="ltr" translate="no">telemetry.  consumers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">telemetry.  consumers.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.logsWriter" class="role-title add-link" data-text="Cloud Telemetry Logs Writer Beta" tabindex="-1">Cloud Telemetry Logs Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.logsWriter</code> )</p>
<p>Access to write logs.</p></td>
<td><p><code dir="ltr" translate="no">logging.logEntries.create</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.metricsWriter" class="role-title add-link" data-text="Cloud Telemetry Metrics Writer" tabindex="-1">Cloud Telemetry Metrics Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.metricsWriter</code> )</p>
<p>Access to write metrics.</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.serviceLogsWriter" class="role-title add-link" data-text="Integrated Service Telemetry Logs Writer Beta" tabindex="-1">Integrated Service Telemetry Logs Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.serviceLogsWriter</code> )</p>
<p>Allows an onboarded service to write log data to a destination.</p></td>
<td><p><code dir="ltr" translate="no">telemetry.consumers.writeLogs</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.serviceMetricsWriter" class="role-title add-link" data-text="Integrated Service Telemetry Metrics Writer Beta" tabindex="-1">Integrated Service Telemetry Metrics Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.serviceMetricsWriter</code> )</p>
<p>Allows an onboarded service to write metrics data to a destination.</p></td>
<td><p><code dir="ltr" translate="no">telemetry.  consumers.  writeMetrics</code></p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.serviceTelemetryWriter" class="role-title add-link" data-text="Integrated Service Telemetry Writer Beta" tabindex="-1">Integrated Service Telemetry Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.serviceTelemetryWriter</code> )</p>
<p>Allows an onboarded service to write all telemetry data to a destination.</p></td>
<td><p><code dir="ltr" translate="no">telemetry.consumers.writeLogs</code></p>
<p><code dir="ltr" translate="no">telemetry.  consumers.  writeMetrics</code></p>
<p><code dir="ltr" translate="no">telemetry.  consumers.  writeTraces</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.serviceTracesWriter" class="role-title add-link" data-text="Integrated Service Telemetry Traces Writer Beta" tabindex="-1">Integrated Service Telemetry Traces Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.serviceTracesWriter</code> )</p>
<p>Allows an onboarded service to write trace data to a destination.</p></td>
<td><p><code dir="ltr" translate="no">telemetry.  consumers.  writeTraces</code></p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.tracesWriter" class="role-title add-link" data-text="Cloud Telemetry Traces Writer" tabindex="-1">Cloud Telemetry Traces Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.tracesWriter</code> )</p>
<p>Access to write trace spans.</p></td>
<td><p><code dir="ltr" translate="no">telemetry.traces.write</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.writer" class="role-title add-link" data-text="Cloud Telemetry Writer" tabindex="-1">Cloud Telemetry Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  telemetry.writer</code> )</p>
<p>Full access to write all telemetry data.</p></td>
<td><p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">telemetry.traces.write</code></p></td>
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
<td><h4 id="telemetry.consumers.getIamPolicy" class="permission-name add-link" data-text="telemetry.consumers.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">telemetry.  consumers.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.consumerAdmin">Consumer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.consumerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.consumers.setIamPolicy" class="permission-name add-link" data-text="telemetry.consumers.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">telemetry.  consumers.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.consumerAdmin">Consumer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.consumerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.consumers.writeLogs" class="permission-name add-link" data-text="telemetry.consumers.writeLogs" tabindex="-1"><code dir="ltr" translate="no">telemetry.consumers.writeLogs</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceLogsWriter">Integrated Service Telemetry Logs Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.serviceLogsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTelemetryWriter">Integrated Service Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.serviceTelemetryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.consumers.writeMetrics" class="permission-name add-link" data-text="telemetry.consumers.writeMetrics" tabindex="-1"><code dir="ltr" translate="no">telemetry.  consumers.  writeMetrics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceMetricsWriter">Integrated Service Telemetry Metrics Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.serviceMetricsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTelemetryWriter">Integrated Service Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.serviceTelemetryWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telemetry.consumers.writeTraces" class="permission-name add-link" data-text="telemetry.consumers.writeTraces" tabindex="-1"><code dir="ltr" translate="no">telemetry.  consumers.  writeTraces</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTelemetryWriter">Integrated Service Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.serviceTelemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.serviceTracesWriter">Integrated Service Telemetry Traces Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.serviceTracesWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telemetry.traces.write" class="permission-name add-link" data-text="telemetry.traces.write" tabindex="-1"><code dir="ltr" translate="no">telemetry.traces.write</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.editor">Telemetry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.agent">Cloud Trace Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.tracesWriter">Cloud Telemetry Traces Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.tracesWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.writer">Cloud Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase Machine Learning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshdataplane.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
