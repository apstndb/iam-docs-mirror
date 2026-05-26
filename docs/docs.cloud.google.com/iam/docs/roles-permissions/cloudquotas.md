---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas
title: Cloud Quotas roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Quotas. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Quotas roles

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
<td><h4 id="cloudquotas.admin" class="role-title add-link" data-text="Cloud Quotas Admin" tabindex="-1">Cloud Quotas Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudquotas.admin</code> )</p>
<p>Full access to Cloud Quotas resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudquotas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudquotas.quotas.get</code></li>
<li><code dir="ltr" translate="no">cloudquotas.quotas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudquotas.viewer" class="role-title add-link" data-text="Cloud Quotas Viewer" tabindex="-1">Cloud Quotas Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudquotas.viewer</code> )</p>
<p>Readonly access to Cloud Quotas resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudquotas.quotas.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Quotas permissions

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
<td><h4 id="cloudquotas.quotas.get" class="permission-name add-link" data-text="cloudquotas.quotas.get" tabindex="-1"><code dir="ltr" translate="no">cloudquotas.quotas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.viewer">Cloud Quotas Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.quotaViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudquotas.quotas.update" class="permission-name add-link" data-text="cloudquotas.quotas.update" tabindex="-1"><code dir="ltr" translate="no">cloudquotas.quotas.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.quotaAdmin</code> )</p></td>
</tr>
</tbody>
</table>
