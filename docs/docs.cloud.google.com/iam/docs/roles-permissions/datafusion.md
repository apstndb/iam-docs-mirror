---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datafusion
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion
title: Cloud Data Fusion roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Data Fusion. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Data Fusion roles

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
<td><h4 id="datafusion.admin" class="role-title add-link" data-text="Cloud Data Fusion Admin" tabindex="-1">Cloud Data Fusion Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p>Full access to Cloud Data Fusion Instances, Namespaces and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">datafusion.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.artifacts.create</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.get</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.list</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.update</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.create</code></li>
<li><code dir="ltr" translate="no">datafusion.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.get</code></li>
<li><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.list</code></li>
<li><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.restart</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.runtime</code></li>
<li><code dir="ltr" translate="no">datafusion.  instances.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.update</code></li>
<li><code dir="ltr" translate="no">datafusion.instances.upgrade</code></li>
<li><code dir="ltr" translate="no">datafusion.locations.get</code></li>
<li><code dir="ltr" translate="no">datafusion.locations.list</code></li>
<li><code dir="ltr" translate="no">datafusion.namespaces.create</code></li>
<li><code dir="ltr" translate="no">datafusion.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datafusion.namespaces.list</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  provisionCredential</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  readRepository</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  setServiceAccount</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  unsetServiceAccount</code></li>
<li><code dir="ltr" translate="no">datafusion.namespaces.update</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  updateRepositoryMetadata</code></li>
<li><code dir="ltr" translate="no">datafusion.  namespaces.  writeRepository</code></li>
<li><code dir="ltr" translate="no">datafusion.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datafusion.operations.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.operations.get</code></li>
<li><code dir="ltr" translate="no">datafusion.operations.list</code></li>
<li><code dir="ltr" translate="no">datafusion.  pipelineConnections.  create</code></li>
<li><code dir="ltr" translate="no">datafusion.  pipelineConnections.  delete</code></li>
<li><code dir="ltr" translate="no">datafusion.  pipelineConnections.  get</code></li>
<li><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></li>
<li><code dir="ltr" translate="no">datafusion.  pipelineConnections.  update</code></li>
<li><code dir="ltr" translate="no">datafusion.  pipelineConnections.  use</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.create</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.execute</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.get</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.list</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.preview</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.update</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.create</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.get</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.list</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.update</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.create</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.  secureKeys.  getSecret</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.list</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.viewer" class="role-title add-link" data-text="Cloud Data Fusion Viewer" tabindex="-1">Cloud Data Fusion Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p>Read-only access to Cloud Data Fusion Instances, Namespaces and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">datafusion.artifacts.get</code></p>
<p><code dir="ltr" translate="no">datafusion.artifacts.list</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datafusion.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.locations.get</code></li>
<li><code dir="ltr" translate="no">datafusion.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datafusion.namespaces.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.get</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  get</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.get</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.list</code></p>
<p><code dir="ltr" translate="no">datafusion.profiles.get</code></p>
<p><code dir="ltr" translate="no">datafusion.profiles.list</code></p>
<p><code dir="ltr" translate="no">datafusion.secureKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.accessor" class="role-title add-link" data-text="Cloud Data Fusion Accessor Beta" tabindex="-1">Cloud Data Fusion Accessor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p>Read-only access to Cloud Data Fusion Instances. Use it on instance level along with the namespace grants to provide access to the specific namespace.</p></td>
<td><p><code dir="ltr" translate="no">datafusion.instances.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.developer" class="role-title add-link" data-text="Cloud Data Fusion Developer Beta" tabindex="-1">Cloud Data Fusion Developer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p>Access Cloud Data Fusion Instances, develop and run pipelines.</p></td>
<td><p><code dir="ltr" translate="no">datafusion.artifacts.get</code></p>
<p><code dir="ltr" translate="no">datafusion.artifacts.list</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datafusion.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.locations.get</code></li>
<li><code dir="ltr" translate="no">datafusion.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datafusion.namespaces.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  provisionCredential</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  readRepository</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.update</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  writeRepository</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.get</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  get</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  use</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.pipelines.create</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.execute</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.get</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.list</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.preview</code></li>
<li><code dir="ltr" translate="no">datafusion.pipelines.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datafusion.profiles.get</code></p>
<p><code dir="ltr" translate="no">datafusion.profiles.list</code></p>
<p><code dir="ltr" translate="no">datafusion.secureKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.secureKeys.create</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.  secureKeys.  getSecret</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.list</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.operator" class="role-title add-link" data-text="Cloud Data Fusion Operator Beta" tabindex="-1">Cloud Data Fusion Operator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p>Access Cloud Data Fusion Instances, operate namespaces and related resources.</p></td>
<td><p><code dir="ltr" translate="no">datafusion.artifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.artifacts.create</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.get</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.list</code></li>
<li><code dir="ltr" translate="no">datafusion.artifacts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datafusion.instances.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datafusion.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.locations.get</code></li>
<li><code dir="ltr" translate="no">datafusion.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datafusion.namespaces.get</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  provisionCredential</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  readRepository</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  unsetServiceAccount</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.update</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  updateRepositoryMetadata</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  writeRepository</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.get</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  get</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  use</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.create</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.delete</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.execute</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.get</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.list</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.update</code></p>
<p><code dir="ltr" translate="no">datafusion.profiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.profiles.create</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.get</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.list</code></li>
<li><code dir="ltr" translate="no">datafusion.profiles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datafusion.secureKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datafusion.secureKeys.create</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.delete</code></li>
<li><code dir="ltr" translate="no">datafusion.  secureKeys.  getSecret</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.list</code></li>
<li><code dir="ltr" translate="no">datafusion.secureKeys.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.runner" class="role-title add-link" data-text="Cloud Data Fusion Runner" tabindex="-1">Cloud Data Fusion Runner</h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.runner</code> )</p>
<p>Access to Cloud Data Fusion runtime resources.</p></td>
<td><p><code dir="ltr" translate="no">datafusion.instances.runtime</code></p></td>
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
<td><h4 id="datafusion.serviceAgent" class="role-title add-link" data-text="Cloud Data Fusion API Service Agent" tabindex="-1">Cloud Data Fusion API Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</p>
<p>Gives Cloud Data Fusion service account access to Service Networking, Cloud Dataproc, Cloud Storage, BigQuery, Cloud Spanner, and Cloud Bigtable resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.attach</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.create</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.update</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.datasets.create</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.get</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.link</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listSharedDatasetUsage</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.update</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.models.create</code></li>
<li><code dir="ltr" translate="no">bigquery.models.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.models.export</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.list</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.routines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.routines.create</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.get</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.list</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.update</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  create</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">bigquery.rowAccessPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.tables.create</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.createIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.deleteSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.export</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.get</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.replicateData</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.setCategory</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  setColumnDataPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.update</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigtable.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigtable.appProfiles.create</code></li>
<li><code dir="ltr" translate="no">bigtable.appProfiles.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.appProfiles.get</code></li>
<li><code dir="ltr" translate="no">bigtable.appProfiles.list</code></li>
<li><code dir="ltr" translate="no">bigtable.appProfiles.update</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  create</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  delete</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigtable.authorizedViews.get</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.authorizedViews.list</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  mutateRows</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  readRows</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  sampleRowKeys</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.  authorizedViews.  update</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.create</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.get</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.list</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.read</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.restore</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.backups.update</code></li>
<li><code dir="ltr" translate="no">bigtable.clusters.create</code></li>
<li><code dir="ltr" translate="no">bigtable.clusters.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.clusters.get</code></li>
<li><code dir="ltr" translate="no">bigtable.clusters.list</code></li>
<li><code dir="ltr" translate="no">bigtable.clusters.update</code></li>
<li><code dir="ltr" translate="no">bigtable.hotTablets.list</code></li>
<li><code dir="ltr" translate="no">bigtable.instances.create</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigtable.instances.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  executeQuery</code></li>
<li><code dir="ltr" translate="no">bigtable.instances.get</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.instances.list</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigtable.instances.ping</code></li>
<li><code dir="ltr" translate="no">bigtable.  instances.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.instances.update</code></li>
<li><code dir="ltr" translate="no">bigtable.keyvisualizer.get</code></li>
<li><code dir="ltr" translate="no">bigtable.keyvisualizer.list</code></li>
<li><code dir="ltr" translate="no">bigtable.locations.list</code></li>
<li><code dir="ltr" translate="no">bigtable.logicalViews.create</code></li>
<li><code dir="ltr" translate="no">bigtable.logicalViews.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.logicalViews.get</code></li>
<li><code dir="ltr" translate="no">bigtable.  logicalViews.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.logicalViews.list</code></li>
<li><code dir="ltr" translate="no">bigtable.logicalViews.readRows</code></li>
<li><code dir="ltr" translate="no">bigtable.  logicalViews.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.logicalViews.update</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  create</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  delete</code></li>
<li><code dir="ltr" translate="no">bigtable.materializedViews.get</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  list</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  readRows</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  sampleRowKeys</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.  materializedViews.  update</code></li>
<li><code dir="ltr" translate="no">bigtable.memoryLayers.get</code></li>
<li><code dir="ltr" translate="no">bigtable.memoryLayers.list</code></li>
<li><code dir="ltr" translate="no">bigtable.memoryLayers.update</code></li>
<li><code dir="ltr" translate="no">bigtable.schemaBundles.create</code></li>
<li><code dir="ltr" translate="no">bigtable.schemaBundles.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.schemaBundles.get</code></li>
<li><code dir="ltr" translate="no">bigtable.  schemaBundles.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.schemaBundles.list</code></li>
<li><code dir="ltr" translate="no">bigtable.  schemaBundles.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.schemaBundles.update</code></li>
<li><code dir="ltr" translate="no">bigtable.  tables.  checkConsistency</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.create</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.delete</code></li>
<li><code dir="ltr" translate="no">bigtable.  tables.  generateConsistencyToken</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.get</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.list</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.mutateRows</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.readRows</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.sampleRowKeys</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.undelete</code></li>
<li><code dir="ltr" translate="no">bigtable.tables.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.get</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.list</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.get</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.disks.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.images.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.instanceSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.interconnectGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.interconnects.get</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getRegionEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.get</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.get</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.datascans.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.create</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.get</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.list</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.run</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  create</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  get</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  list</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  update</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  use</code></p>
<p><code dir="ltr" translate="no">dataproc.batches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataproc.batches.analyze</code></li>
<li><code dir="ltr" translate="no">dataproc.batches.cancel</code></li>
<li><code dir="ltr" translate="no">dataproc.batches.create</code></li>
<li><code dir="ltr" translate="no">dataproc.batches.delete</code></li>
<li><code dir="ltr" translate="no">dataproc.batches.get</code></li>
<li><code dir="ltr" translate="no">dataproc.batches.list</code></li>
<li><code dir="ltr" translate="no">dataproc.  batches.  sparkApplicationRead</code></li>
<li><code dir="ltr" translate="no">dataproc.  batches.  sparkApplicationWrite</code></li>
</ul>
<p><code dir="ltr" translate="no">dataproc.clusters.create</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.delete</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.get</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.list</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.repair</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.start</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.stop</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.update</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.use</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.cancel</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.create</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.delete</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.get</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.list</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.update</code></p>
<p><code dir="ltr" translate="no">dataproc.nodeGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataproc.nodeGroups.create</code></li>
<li><code dir="ltr" translate="no">dataproc.nodeGroups.get</code></li>
<li><code dir="ltr" translate="no">dataproc.nodeGroups.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataproc.operations.cancel</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.delete</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.get</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.list</code></p>
<p><code dir="ltr" translate="no">dataproc.sessionTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataproc.  sessionTemplates.  create</code></li>
<li><code dir="ltr" translate="no">dataproc.  sessionTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">dataproc.sessionTemplates.get</code></li>
<li><code dir="ltr" translate="no">dataproc.sessionTemplates.list</code></li>
<li><code dir="ltr" translate="no">dataproc.  sessionTemplates.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataproc.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataproc.sessions.create</code></li>
<li><code dir="ltr" translate="no">dataproc.sessions.delete</code></li>
<li><code dir="ltr" translate="no">dataproc.sessions.get</code></li>
<li><code dir="ltr" translate="no">dataproc.sessions.list</code></li>
<li><code dir="ltr" translate="no">dataproc.  sessions.  sparkApplicationRead</code></li>
<li><code dir="ltr" translate="no">dataproc.  sessions.  sparkApplicationWrite</code></li>
<li><code dir="ltr" translate="no">dataproc.sessions.terminate</code></li>
</ul>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  create</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">dataproc.workflowTemplates.get</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  instantiate</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  instantiateInline</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  list</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  update</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataprocrm.nodePools.create</code></li>
<li><code dir="ltr" translate="no">dataprocrm.nodePools.delete</code></li>
<li><code dir="ltr" translate="no">dataprocrm.  nodePools.  deleteNodes</code></li>
<li><code dir="ltr" translate="no">dataprocrm.nodePools.get</code></li>
<li><code dir="ltr" translate="no">dataprocrm.nodePools.list</code></li>
<li><code dir="ltr" translate="no">dataprocrm.nodePools.resize</code></li>
</ul>
<p><code dir="ltr" translate="no">dataprocrm.nodes.get</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodes.heartbeat</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodes.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodes.update</code></p>
<p><code dir="ltr" translate="no">dataprocrm.operations.get</code></p>
<p><code dir="ltr" translate="no">dataprocrm.operations.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.workloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataprocrm.workloads.cancel</code></li>
<li><code dir="ltr" translate="no">dataprocrm.workloads.create</code></li>
<li><code dir="ltr" translate="no">dataprocrm.workloads.delete</code></li>
<li><code dir="ltr" translate="no">dataprocrm.workloads.get</code></li>
<li><code dir="ltr" translate="no">dataprocrm.workloads.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.locations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.operations.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  agentGateways.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  agentGateways.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.get</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.list</code></p>
<p><code dir="ltr" translate="no">networkservices.grpcRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.httpRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.locations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.meshes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.operations.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.route_views.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  route_views.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  route_views.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  serviceBindings.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceBindings.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">spanner.databaseOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.databaseOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.databases.adapt</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginPartitionedDmlTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.changequorum</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.updateDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.write</code></p>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.get</code></p>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.anywhereCaches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.anywhereCaches.create</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.disable</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.get</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.list</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.pause</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.resume</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.bucketOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  bucketOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.get</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.buckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.buckets.create</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.buckets.delete</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  enableObjectRetention</code></li>
<li><code dir="ltr" translate="no">storage.buckets.get</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  getObjectInsights</code></li>
<li><code dir="ltr" translate="no">storage.buckets.list</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">storage.buckets.relocate</code></li>
<li><code dir="ltr" translate="no">storage.buckets.restore</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.buckets.update</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.featureConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.featureConfigs.create</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.delete</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.get</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.list</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.intelligenceConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></li>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.managedFolders.create</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.delete</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.get</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.list</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.multipartUploads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.multipartUploads.abort</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></li>
<li><code dir="ltr" translate="no">storage.multipartUploads.list</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.objects.create</code></li>
<li><code dir="ltr" translate="no">storage.objects.createContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.delete</code></li>
<li><code dir="ltr" translate="no">storage.objects.deleteContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.get</code></li>
<li><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.list</code></li>
<li><code dir="ltr" translate="no">storage.objects.move</code></li>
<li><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.restore</code></li>
<li><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.setRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.update</code></li>
<li><code dir="ltr" translate="no">storage.objects.updateContext</code></li>
</ul>
<p><code dir="ltr" translate="no">storagebatchoperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  create</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">trafficdirector.*</code></p>
<ul>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></li>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  reportMetrics</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Cloud Data Fusion permissions

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
<td><h4 id="datafusion.artifacts.create" class="permission-name add-link" data-text="datafusion.artifacts.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.artifacts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.artifacts.delete" class="permission-name add-link" data-text="datafusion.artifacts.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.artifacts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.artifacts.get" class="permission-name add-link" data-text="datafusion.artifacts.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.artifacts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.artifacts.list" class="permission-name add-link" data-text="datafusion.artifacts.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.artifacts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.artifacts.update" class="permission-name add-link" data-text="datafusion.artifacts.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.artifacts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.create" class="permission-name add-link" data-text="datafusion.instances.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.createTagBinding" class="permission-name add-link" data-text="datafusion.instances.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datafusion.  instances.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.delete" class="permission-name add-link" data-text="datafusion.instances.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.deleteTagBinding" class="permission-name add-link" data-text="datafusion.instances.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datafusion.  instances.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.get" class="permission-name add-link" data-text="datafusion.instances.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.getIamPolicy" class="permission-name add-link" data-text="datafusion.instances.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.list" class="permission-name add-link" data-text="datafusion.instances.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.listEffectiveTags" class="permission-name add-link" data-text="datafusion.instances.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.listTagBindings" class="permission-name add-link" data-text="datafusion.instances.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.restart" class="permission-name add-link" data-text="datafusion.instances.restart" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.restart</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.runtime" class="permission-name add-link" data-text="datafusion.instances.runtime" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.runtime</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.runner">Cloud Data Fusion Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.runner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.setIamPolicy" class="permission-name add-link" data-text="datafusion.instances.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datafusion.  instances.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.instances.update" class="permission-name add-link" data-text="datafusion.instances.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.instances.upgrade" class="permission-name add-link" data-text="datafusion.instances.upgrade" tabindex="-1"><code dir="ltr" translate="no">datafusion.instances.upgrade</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.locations.get" class="permission-name add-link" data-text="datafusion.locations.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.locations.list" class="permission-name add-link" data-text="datafusion.locations.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.create" class="permission-name add-link" data-text="datafusion.namespaces.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.namespaces.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.namespaces.delete" class="permission-name add-link" data-text="datafusion.namespaces.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.namespaces.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.get" class="permission-name add-link" data-text="datafusion.namespaces.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.namespaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.namespaces.getIamPolicy" class="permission-name add-link" data-text="datafusion.namespaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.list" class="permission-name add-link" data-text="datafusion.namespaces.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.namespaces.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.namespaces.provisionCredential" class="permission-name add-link" data-text="datafusion.namespaces.provisionCredential" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  provisionCredential</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.readRepository" class="permission-name add-link" data-text="datafusion.namespaces.readRepository" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  readRepository</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.namespaces.setIamPolicy" class="permission-name add-link" data-text="datafusion.namespaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.setServiceAccount" class="permission-name add-link" data-text="datafusion.namespaces.setServiceAccount" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  setServiceAccount</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.namespaces.unsetServiceAccount" class="permission-name add-link" data-text="datafusion.namespaces.unsetServiceAccount" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  unsetServiceAccount</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.update" class="permission-name add-link" data-text="datafusion.namespaces.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.namespaces.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.namespaces.updateRepositoryMetadata" class="permission-name add-link" data-text="datafusion.namespaces.updateRepositoryMetadata" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  updateRepositoryMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.namespaces.writeRepository" class="permission-name add-link" data-text="datafusion.namespaces.writeRepository" tabindex="-1"><code dir="ltr" translate="no">datafusion.  namespaces.  writeRepository</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.operations.cancel" class="permission-name add-link" data-text="datafusion.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">datafusion.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.operations.delete" class="permission-name add-link" data-text="datafusion.operations.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.operations.get" class="permission-name add-link" data-text="datafusion.operations.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.operations.list" class="permission-name add-link" data-text="datafusion.operations.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelineConnections.create" class="permission-name add-link" data-text="datafusion.pipelineConnections.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.  pipelineConnections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.pipelineConnections.delete" class="permission-name add-link" data-text="datafusion.pipelineConnections.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.  pipelineConnections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelineConnections.get" class="permission-name add-link" data-text="datafusion.pipelineConnections.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.  pipelineConnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.pipelineConnections.list" class="permission-name add-link" data-text="datafusion.pipelineConnections.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelineConnections.update" class="permission-name add-link" data-text="datafusion.pipelineConnections.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.  pipelineConnections.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.pipelineConnections.use" class="permission-name add-link" data-text="datafusion.pipelineConnections.use" tabindex="-1"><code dir="ltr" translate="no">datafusion.  pipelineConnections.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelines.create" class="permission-name add-link" data-text="datafusion.pipelines.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.pipelines.delete" class="permission-name add-link" data-text="datafusion.pipelines.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelines.execute" class="permission-name add-link" data-text="datafusion.pipelines.execute" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.pipelines.get" class="permission-name add-link" data-text="datafusion.pipelines.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelines.list" class="permission-name add-link" data-text="datafusion.pipelines.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.pipelines.preview" class="permission-name add-link" data-text="datafusion.pipelines.preview" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.preview</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.pipelines.update" class="permission-name add-link" data-text="datafusion.pipelines.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.pipelines.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.profiles.create" class="permission-name add-link" data-text="datafusion.profiles.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.profiles.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.profiles.delete" class="permission-name add-link" data-text="datafusion.profiles.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.profiles.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.profiles.get" class="permission-name add-link" data-text="datafusion.profiles.get" tabindex="-1"><code dir="ltr" translate="no">datafusion.profiles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.profiles.list" class="permission-name add-link" data-text="datafusion.profiles.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.profiles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.profiles.update" class="permission-name add-link" data-text="datafusion.profiles.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.profiles.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.secureKeys.create" class="permission-name add-link" data-text="datafusion.secureKeys.create" tabindex="-1"><code dir="ltr" translate="no">datafusion.secureKeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.secureKeys.delete" class="permission-name add-link" data-text="datafusion.secureKeys.delete" tabindex="-1"><code dir="ltr" translate="no">datafusion.secureKeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.secureKeys.getSecret" class="permission-name add-link" data-text="datafusion.secureKeys.getSecret" tabindex="-1"><code dir="ltr" translate="no">datafusion.  secureKeys.  getSecret</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datafusion.secureKeys.list" class="permission-name add-link" data-text="datafusion.secureKeys.list" tabindex="-1"><code dir="ltr" translate="no">datafusion.secureKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datafusion.secureKeys.update" class="permission-name add-link" data-text="datafusion.secureKeys.update" tabindex="-1"><code dir="ltr" translate="no">datafusion.secureKeys.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p></td>
</tr>
</tbody>
</table>
