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
<td>Cloud Data Fusion Admin
<p>( <code>roles/ datafusion.admin</code> )</p>
<p>Full access to Cloud Data Fusion Instances, Namespaces and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>datafusion.*</code></p>
<ul>
<li><code>datafusion.artifacts.create</code></li>
<li><code>datafusion.artifacts.delete</code></li>
<li><code>datafusion.artifacts.get</code></li>
<li><code>datafusion.artifacts.list</code></li>
<li><code>datafusion.artifacts.update</code></li>
<li><code>datafusion.instances.create</code></li>
<li><code>datafusion. instances. createTagBinding</code></li>
<li><code>datafusion.instances.delete</code></li>
<li><code>datafusion. instances. deleteTagBinding</code></li>
<li><code>datafusion.instances.get</code></li>
<li><code>datafusion. instances. getIamPolicy</code></li>
<li><code>datafusion.instances.list</code></li>
<li><code>datafusion. instances. listEffectiveTags</code></li>
<li><code>datafusion. instances. listTagBindings</code></li>
<li><code>datafusion.instances.restart</code></li>
<li><code>datafusion.instances.runtime</code></li>
<li><code>datafusion. instances. setIamPolicy</code></li>
<li><code>datafusion.instances.update</code></li>
<li><code>datafusion.instances.upgrade</code></li>
<li><code>datafusion.locations.get</code></li>
<li><code>datafusion.locations.list</code></li>
<li><code>datafusion.namespaces.create</code></li>
<li><code>datafusion.namespaces.delete</code></li>
<li><code>datafusion.namespaces.get</code></li>
<li><code>datafusion. namespaces. getIamPolicy</code></li>
<li><code>datafusion.namespaces.list</code></li>
<li><code>datafusion. namespaces. provisionCredential</code></li>
<li><code>datafusion. namespaces. readRepository</code></li>
<li><code>datafusion. namespaces. setIamPolicy</code></li>
<li><code>datafusion. namespaces. setServiceAccount</code></li>
<li><code>datafusion. namespaces. unsetServiceAccount</code></li>
<li><code>datafusion.namespaces.update</code></li>
<li><code>datafusion. namespaces. updateRepositoryMetadata</code></li>
<li><code>datafusion. namespaces. writeRepository</code></li>
<li><code>datafusion.operations.cancel</code></li>
<li><code>datafusion.operations.delete</code></li>
<li><code>datafusion.operations.get</code></li>
<li><code>datafusion.operations.list</code></li>
<li><code>datafusion. pipelineConnections. create</code></li>
<li><code>datafusion. pipelineConnections. delete</code></li>
<li><code>datafusion. pipelineConnections. get</code></li>
<li><code>datafusion. pipelineConnections. list</code></li>
<li><code>datafusion. pipelineConnections. update</code></li>
<li><code>datafusion. pipelineConnections. use</code></li>
<li><code>datafusion.pipelines.create</code></li>
<li><code>datafusion.pipelines.delete</code></li>
<li><code>datafusion.pipelines.execute</code></li>
<li><code>datafusion.pipelines.get</code></li>
<li><code>datafusion.pipelines.list</code></li>
<li><code>datafusion.pipelines.preview</code></li>
<li><code>datafusion.pipelines.update</code></li>
<li><code>datafusion.profiles.create</code></li>
<li><code>datafusion.profiles.delete</code></li>
<li><code>datafusion.profiles.get</code></li>
<li><code>datafusion.profiles.list</code></li>
<li><code>datafusion.profiles.update</code></li>
<li><code>datafusion.secureKeys.create</code></li>
<li><code>datafusion.secureKeys.delete</code></li>
<li><code>datafusion. secureKeys. getSecret</code></li>
<li><code>datafusion.secureKeys.list</code></li>
<li><code>datafusion.secureKeys.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Data Fusion Viewer
<p>( <code>roles/ datafusion.viewer</code> )</p>
<p>Read-only access to Cloud Data Fusion Instances, Namespaces and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>datafusion.artifacts.get</code></p>
<p><code>datafusion.artifacts.list</code></p>
<p><code>datafusion.instances.get</code></p>
<p><code>datafusion. instances. getIamPolicy</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datafusion.locations.*</code></p>
<ul>
<li><code>datafusion.locations.get</code></li>
<li><code>datafusion.locations.list</code></li>
</ul>
<p><code>datafusion.namespaces.get</code></p>
<p><code>datafusion. namespaces. getIamPolicy</code></p>
<p><code>datafusion.namespaces.list</code></p>
<p><code>datafusion.operations.get</code></p>
<p><code>datafusion.operations.list</code></p>
<p><code>datafusion. pipelineConnections. get</code></p>
<p><code>datafusion. pipelineConnections. list</code></p>
<p><code>datafusion.pipelines.get</code></p>
<p><code>datafusion.pipelines.list</code></p>
<p><code>datafusion.profiles.get</code></p>
<p><code>datafusion.profiles.list</code></p>
<p><code>datafusion.secureKeys.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Data Fusion Accessor <sup>Beta</sup>
<p>( <code>roles/ datafusion.accessor</code> )</p>
<p>Read-only access to Cloud Data Fusion Instances. Use it on instance level along with the namespace grants to provide access to the specific namespace.</p></td>
<td><p><code>datafusion.instances.get</code></p>
<p><code>datafusion. instances. getIamPolicy</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Data Fusion Developer <sup>Beta</sup>
<p>( <code>roles/ datafusion.developer</code> )</p>
<p>Access Cloud Data Fusion Instances, develop and run pipelines.</p></td>
<td><p><code>datafusion.artifacts.get</code></p>
<p><code>datafusion.artifacts.list</code></p>
<p><code>datafusion.instances.get</code></p>
<p><code>datafusion. instances. getIamPolicy</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datafusion.locations.*</code></p>
<ul>
<li><code>datafusion.locations.get</code></li>
<li><code>datafusion.locations.list</code></li>
</ul>
<p><code>datafusion.namespaces.get</code></p>
<p><code>datafusion. namespaces. getIamPolicy</code></p>
<p><code>datafusion.namespaces.list</code></p>
<p><code>datafusion. namespaces. provisionCredential</code></p>
<p><code>datafusion. namespaces. readRepository</code></p>
<p><code>datafusion.namespaces.update</code></p>
<p><code>datafusion. namespaces. writeRepository</code></p>
<p><code>datafusion.operations.get</code></p>
<p><code>datafusion.operations.list</code></p>
<p><code>datafusion. pipelineConnections. get</code></p>
<p><code>datafusion. pipelineConnections. list</code></p>
<p><code>datafusion. pipelineConnections. use</code></p>
<p><code>datafusion.pipelines.*</code></p>
<ul>
<li><code>datafusion.pipelines.create</code></li>
<li><code>datafusion.pipelines.delete</code></li>
<li><code>datafusion.pipelines.execute</code></li>
<li><code>datafusion.pipelines.get</code></li>
<li><code>datafusion.pipelines.list</code></li>
<li><code>datafusion.pipelines.preview</code></li>
<li><code>datafusion.pipelines.update</code></li>
</ul>
<p><code>datafusion.profiles.get</code></p>
<p><code>datafusion.profiles.list</code></p>
<p><code>datafusion.secureKeys.*</code></p>
<ul>
<li><code>datafusion.secureKeys.create</code></li>
<li><code>datafusion.secureKeys.delete</code></li>
<li><code>datafusion. secureKeys. getSecret</code></li>
<li><code>datafusion.secureKeys.list</code></li>
<li><code>datafusion.secureKeys.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Data Fusion Operator <sup>Beta</sup>
<p>( <code>roles/ datafusion.operator</code> )</p>
<p>Access Cloud Data Fusion Instances, operate namespaces and related resources.</p></td>
<td><p><code>datafusion.artifacts.*</code></p>
<ul>
<li><code>datafusion.artifacts.create</code></li>
<li><code>datafusion.artifacts.delete</code></li>
<li><code>datafusion.artifacts.get</code></li>
<li><code>datafusion.artifacts.list</code></li>
<li><code>datafusion.artifacts.update</code></li>
</ul>
<p><code>datafusion.instances.get</code></p>
<p><code>datafusion. instances. getIamPolicy</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datafusion.locations.*</code></p>
<ul>
<li><code>datafusion.locations.get</code></li>
<li><code>datafusion.locations.list</code></li>
</ul>
<p><code>datafusion.namespaces.get</code></p>
<p><code>datafusion. namespaces. getIamPolicy</code></p>
<p><code>datafusion.namespaces.list</code></p>
<p><code>datafusion. namespaces. provisionCredential</code></p>
<p><code>datafusion. namespaces. readRepository</code></p>
<p><code>datafusion. namespaces. setServiceAccount</code></p>
<p><code>datafusion. namespaces. unsetServiceAccount</code></p>
<p><code>datafusion.namespaces.update</code></p>
<p><code>datafusion. namespaces. updateRepositoryMetadata</code></p>
<p><code>datafusion. namespaces. writeRepository</code></p>
<p><code>datafusion.operations.get</code></p>
<p><code>datafusion.operations.list</code></p>
<p><code>datafusion. pipelineConnections. get</code></p>
<p><code>datafusion. pipelineConnections. list</code></p>
<p><code>datafusion. pipelineConnections. use</code></p>
<p><code>datafusion.pipelines.create</code></p>
<p><code>datafusion.pipelines.delete</code></p>
<p><code>datafusion.pipelines.execute</code></p>
<p><code>datafusion.pipelines.get</code></p>
<p><code>datafusion.pipelines.list</code></p>
<p><code>datafusion.pipelines.update</code></p>
<p><code>datafusion.profiles.*</code></p>
<ul>
<li><code>datafusion.profiles.create</code></li>
<li><code>datafusion.profiles.delete</code></li>
<li><code>datafusion.profiles.get</code></li>
<li><code>datafusion.profiles.list</code></li>
<li><code>datafusion.profiles.update</code></li>
</ul>
<p><code>datafusion.secureKeys.*</code></p>
<ul>
<li><code>datafusion.secureKeys.create</code></li>
<li><code>datafusion.secureKeys.delete</code></li>
<li><code>datafusion. secureKeys. getSecret</code></li>
<li><code>datafusion.secureKeys.list</code></li>
<li><code>datafusion.secureKeys.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Data Fusion Runner
<p>( <code>roles/ datafusion.runner</code> )</p>
<p>Access to Cloud Data Fusion runtime resources.</p></td>
<td><p><code>datafusion.instances.runtime</code></p></td>
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
<td>Cloud Data Fusion API Service Agent
<p>( <code>roles/ datafusion.serviceAgent</code> )</p>
<p>Gives Cloud Data Fusion service account access to Service Networking, Cloud Dataproc, Cloud Storage, BigQuery, Cloud Spanner, and Cloud Bigtable resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.config.get</code></p>
<p><code>bigquery.dataPolicies.attach</code></p>
<p><code>bigquery.dataPolicies.create</code></p>
<p><code>bigquery.dataPolicies.delete</code></p>
<p><code>bigquery.dataPolicies.get</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery. dataPolicies. setIamPolicy</code></p>
<p><code>bigquery.dataPolicies.update</code></p>
<p><code>bigquery.datasets.*</code></p>
<ul>
<li><code>bigquery.datasets.create</code></li>
<li><code>bigquery. datasets. createTagBinding</code></li>
<li><code>bigquery.datasets.delete</code></li>
<li><code>bigquery. datasets. deleteTagBinding</code></li>
<li><code>bigquery.datasets.get</code></li>
<li><code>bigquery.datasets.getIamPolicy</code></li>
<li><code>bigquery.datasets.link</code></li>
<li><code>bigquery. datasets. listEffectiveTags</code></li>
<li><code>bigquery. datasets. listSharedDatasetUsage</code></li>
<li><code>bigquery. datasets. listTagBindings</code></li>
<li><code>bigquery.datasets.setIamPolicy</code></li>
<li><code>bigquery.datasets.update</code></li>
<li><code>bigquery.datasets.updateTag</code></li>
</ul>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.models.*</code></p>
<ul>
<li><code>bigquery.models.create</code></li>
<li><code>bigquery.models.delete</code></li>
<li><code>bigquery.models.export</code></li>
<li><code>bigquery.models.getData</code></li>
<li><code>bigquery.models.getMetadata</code></li>
<li><code>bigquery.models.list</code></li>
<li><code>bigquery.models.updateData</code></li>
<li><code>bigquery.models.updateMetadata</code></li>
<li><code>bigquery.models.updateTag</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.routines.*</code></p>
<ul>
<li><code>bigquery.routines.create</code></li>
<li><code>bigquery.routines.delete</code></li>
<li><code>bigquery.routines.get</code></li>
<li><code>bigquery.routines.list</code></li>
<li><code>bigquery.routines.update</code></li>
<li><code>bigquery.routines.updateTag</code></li>
</ul>
<p><code>bigquery. rowAccessPolicies. create</code></p>
<p><code>bigquery. rowAccessPolicies. delete</code></p>
<p><code>bigquery.rowAccessPolicies.get</code></p>
<p><code>bigquery. rowAccessPolicies. getIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. list</code></p>
<p><code>bigquery. rowAccessPolicies. setIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. update</code></p>
<p><code>bigquery.tables.*</code></p>
<ul>
<li><code>bigquery.tables.create</code></li>
<li><code>bigquery.tables.createIndex</code></li>
<li><code>bigquery.tables.createSnapshot</code></li>
<li><code>bigquery. tables. createTagBinding</code></li>
<li><code>bigquery.tables.delete</code></li>
<li><code>bigquery.tables.deleteIndex</code></li>
<li><code>bigquery.tables.deleteSnapshot</code></li>
<li><code>bigquery. tables. deleteTagBinding</code></li>
<li><code>bigquery.tables.export</code></li>
<li><code>bigquery.tables.get</code></li>
<li><code>bigquery.tables.getData</code></li>
<li><code>bigquery.tables.getIamPolicy</code></li>
<li><code>bigquery.tables.list</code></li>
<li><code>bigquery. tables. listEffectiveTags</code></li>
<li><code>bigquery. tables. listTagBindings</code></li>
<li><code>bigquery.tables.replicateData</code></li>
<li><code>bigquery. tables. restoreSnapshot</code></li>
<li><code>bigquery.tables.setCategory</code></li>
<li><code>bigquery. tables. setColumnDataPolicy</code></li>
<li><code>bigquery.tables.setIamPolicy</code></li>
<li><code>bigquery.tables.update</code></li>
<li><code>bigquery.tables.updateData</code></li>
<li><code>bigquery.tables.updateIndex</code></li>
<li><code>bigquery.tables.updateTag</code></li>
</ul>
<p><code>bigtable.*</code></p>
<ul>
<li><code>bigtable.appProfiles.create</code></li>
<li><code>bigtable.appProfiles.delete</code></li>
<li><code>bigtable.appProfiles.get</code></li>
<li><code>bigtable.appProfiles.list</code></li>
<li><code>bigtable.appProfiles.update</code></li>
<li><code>bigtable. authorizedViews. create</code></li>
<li><code>bigtable. authorizedViews. createTagBinding</code></li>
<li><code>bigtable. authorizedViews. delete</code></li>
<li><code>bigtable. authorizedViews. deleteTagBinding</code></li>
<li><code>bigtable.authorizedViews.get</code></li>
<li><code>bigtable. authorizedViews. getIamPolicy</code></li>
<li><code>bigtable.authorizedViews.list</code></li>
<li><code>bigtable. authorizedViews. listEffectiveTags</code></li>
<li><code>bigtable. authorizedViews. listTagBindings</code></li>
<li><code>bigtable. authorizedViews. mutateRows</code></li>
<li><code>bigtable. authorizedViews. readRows</code></li>
<li><code>bigtable. authorizedViews. sampleRowKeys</code></li>
<li><code>bigtable. authorizedViews. setIamPolicy</code></li>
<li><code>bigtable. authorizedViews. update</code></li>
<li><code>bigtable.backups.create</code></li>
<li><code>bigtable.backups.delete</code></li>
<li><code>bigtable.backups.get</code></li>
<li><code>bigtable.backups.getIamPolicy</code></li>
<li><code>bigtable.backups.list</code></li>
<li><code>bigtable.backups.read</code></li>
<li><code>bigtable.backups.restore</code></li>
<li><code>bigtable.backups.setIamPolicy</code></li>
<li><code>bigtable.backups.update</code></li>
<li><code>bigtable.clusters.create</code></li>
<li><code>bigtable.clusters.delete</code></li>
<li><code>bigtable.clusters.get</code></li>
<li><code>bigtable.clusters.list</code></li>
<li><code>bigtable.clusters.update</code></li>
<li><code>bigtable.hotTablets.list</code></li>
<li><code>bigtable.instances.create</code></li>
<li><code>bigtable. instances. createTagBinding</code></li>
<li><code>bigtable.instances.delete</code></li>
<li><code>bigtable. instances. deleteTagBinding</code></li>
<li><code>bigtable. instances. executeQuery</code></li>
<li><code>bigtable.instances.get</code></li>
<li><code>bigtable. instances. getIamPolicy</code></li>
<li><code>bigtable.instances.list</code></li>
<li><code>bigtable. instances. listEffectiveTags</code></li>
<li><code>bigtable. instances. listTagBindings</code></li>
<li><code>bigtable.instances.ping</code></li>
<li><code>bigtable. instances. setIamPolicy</code></li>
<li><code>bigtable.instances.update</code></li>
<li><code>bigtable.keyvisualizer.get</code></li>
<li><code>bigtable.keyvisualizer.list</code></li>
<li><code>bigtable.locations.list</code></li>
<li><code>bigtable.logicalViews.create</code></li>
<li><code>bigtable.logicalViews.delete</code></li>
<li><code>bigtable.logicalViews.get</code></li>
<li><code>bigtable. logicalViews. getIamPolicy</code></li>
<li><code>bigtable.logicalViews.list</code></li>
<li><code>bigtable.logicalViews.readRows</code></li>
<li><code>bigtable. logicalViews. setIamPolicy</code></li>
<li><code>bigtable.logicalViews.update</code></li>
<li><code>bigtable. materializedViews. create</code></li>
<li><code>bigtable. materializedViews. delete</code></li>
<li><code>bigtable.materializedViews.get</code></li>
<li><code>bigtable. materializedViews. getIamPolicy</code></li>
<li><code>bigtable. materializedViews. list</code></li>
<li><code>bigtable. materializedViews. readRows</code></li>
<li><code>bigtable. materializedViews. sampleRowKeys</code></li>
<li><code>bigtable. materializedViews. setIamPolicy</code></li>
<li><code>bigtable. materializedViews. update</code></li>
<li><code>bigtable.memoryLayers.get</code></li>
<li><code>bigtable.memoryLayers.list</code></li>
<li><code>bigtable.memoryLayers.update</code></li>
<li><code>bigtable.schemaBundles.create</code></li>
<li><code>bigtable.schemaBundles.delete</code></li>
<li><code>bigtable.schemaBundles.get</code></li>
<li><code>bigtable. schemaBundles. getIamPolicy</code></li>
<li><code>bigtable.schemaBundles.list</code></li>
<li><code>bigtable. schemaBundles. setIamPolicy</code></li>
<li><code>bigtable.schemaBundles.update</code></li>
<li><code>bigtable. tables. checkConsistency</code></li>
<li><code>bigtable.tables.create</code></li>
<li><code>bigtable.tables.delete</code></li>
<li><code>bigtable. tables. generateConsistencyToken</code></li>
<li><code>bigtable.tables.get</code></li>
<li><code>bigtable.tables.getIamPolicy</code></li>
<li><code>bigtable.tables.list</code></li>
<li><code>bigtable.tables.mutateRows</code></li>
<li><code>bigtable.tables.readRows</code></li>
<li><code>bigtable.tables.sampleRowKeys</code></li>
<li><code>bigtable.tables.setIamPolicy</code></li>
<li><code>bigtable.tables.undelete</code></li>
<li><code>bigtable.tables.update</code></li>
</ul>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute.autoscalers.get</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute.backendBuckets.get</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute.crossSiteNetworks.get</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalFrontendSettings. get</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute. instanceGroupManagers. listEffectiveTags</code></p>
<p><code>compute. instanceGroupManagers. listTagBindings</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute. instanceGroups. listEffectiveTags</code></p>
<p><code>compute. instanceGroups. listTagBindings</code></p>
<p><code>compute.instanceSettings.get</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute. instances. getScreenshot</code></p>
<p><code>compute. instances. getSerialPortOutput</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listReferrers</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. interconnectAttachmentGroups. get</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
<p><code>compute.interconnectGroups.get</code></p>
<p><code>compute. interconnectGroups. list</code></p>
<p><code>compute. interconnectLocations.*</code></p>
<ul>
<li><code>compute. interconnectLocations. get</code></li>
<li><code>compute. interconnectLocations. list</code></li>
</ul>
<p><code>compute. interconnectRemoteLocations.*</code></p>
<ul>
<li><code>compute. interconnectRemoteLocations. get</code></li>
<li><code>compute. interconnectRemoteLocations. list</code></li>
</ul>
<p><code>compute.interconnects.get</code></p>
<p><code>compute.interconnects.list</code></p>
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkAttachments. update</code></p>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.addPeering</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute. networks. getRegionEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute.networks.removePeering</code></p>
<p><code>compute.networks.update</code></p>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. regionBackendBuckets. get</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionCompositeHealthChecks. get</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionHealthAggregationPolicies. get</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. get</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionHealthSources. get</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkPolicies. get</code></p>
<p><code>compute. regionNetworkPolicies. list</code></p>
<p><code>compute. regionNotificationEndpoints. get</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute.regionSslPolicies.get</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionSslPolicies. listAvailableFeatures</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.getRoutePolicy</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.listBgpRoutes</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listRoutePolicies</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute.sslPolicies.get</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. sslPolicies. listAvailableFeatures</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute.targetGrpcProxies.get</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute.targetInstances.get</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute.targetPools.get</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>compute.wireGroups.get</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataplex.datascans.*</code></p>
<ul>
<li><code>dataplex.datascans.cancel</code></li>
<li><code>dataplex.datascans.create</code></li>
<li><code>dataplex.datascans.delete</code></li>
<li><code>dataplex.datascans.get</code></li>
<li><code>dataplex.datascans.getData</code></li>
<li><code>dataplex. datascans. getIamPolicy</code></li>
<li><code>dataplex.datascans.list</code></li>
<li><code>dataplex.datascans.run</code></li>
<li><code>dataplex. datascans. setIamPolicy</code></li>
<li><code>dataplex.datascans.update</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataproc. autoscalingPolicies. create</code></p>
<p><code>dataproc. autoscalingPolicies. delete</code></p>
<p><code>dataproc. autoscalingPolicies. get</code></p>
<p><code>dataproc. autoscalingPolicies. list</code></p>
<p><code>dataproc. autoscalingPolicies. update</code></p>
<p><code>dataproc. autoscalingPolicies. use</code></p>
<p><code>dataproc.batches.analyze</code></p>
<p><code>dataproc.batches.cancel</code></p>
<p><code>dataproc.batches.create</code></p>
<p><code>dataproc.batches.delete</code></p>
<p><code>dataproc.batches.get</code></p>
<p><code>dataproc.batches.list</code></p>
<p><code>dataproc. batches. sparkApplicationRead</code></p>
<p><code>dataproc. batches. sparkApplicationWrite</code></p>
<p><code>dataproc.clusters.create</code></p>
<p><code>dataproc.clusters.delete</code></p>
<p><code>dataproc.clusters.get</code></p>
<p><code>dataproc.clusters.list</code></p>
<p><code>dataproc.clusters.repair</code></p>
<p><code>dataproc.clusters.start</code></p>
<p><code>dataproc.clusters.stop</code></p>
<p><code>dataproc.clusters.update</code></p>
<p><code>dataproc.clusters.use</code></p>
<p><code>dataproc.jobs.cancel</code></p>
<p><code>dataproc.jobs.create</code></p>
<p><code>dataproc.jobs.delete</code></p>
<p><code>dataproc.jobs.get</code></p>
<p><code>dataproc.jobs.list</code></p>
<p><code>dataproc.jobs.update</code></p>
<p><code>dataproc.nodeGroups.*</code></p>
<ul>
<li><code>dataproc.nodeGroups.create</code></li>
<li><code>dataproc.nodeGroups.get</code></li>
<li><code>dataproc.nodeGroups.update</code></li>
</ul>
<p><code>dataproc.operations.cancel</code></p>
<p><code>dataproc.operations.delete</code></p>
<p><code>dataproc.operations.get</code></p>
<p><code>dataproc.operations.list</code></p>
<p><code>dataproc.sessionTemplates.*</code></p>
<ul>
<li><code>dataproc. sessionTemplates. create</code></li>
<li><code>dataproc. sessionTemplates. delete</code></li>
<li><code>dataproc.sessionTemplates.get</code></li>
<li><code>dataproc.sessionTemplates.list</code></li>
<li><code>dataproc. sessionTemplates. update</code></li>
</ul>
<p><code>dataproc.sessions.*</code></p>
<ul>
<li><code>dataproc.sessions.create</code></li>
<li><code>dataproc.sessions.delete</code></li>
<li><code>dataproc.sessions.get</code></li>
<li><code>dataproc.sessions.list</code></li>
<li><code>dataproc. sessions. sparkApplicationRead</code></li>
<li><code>dataproc. sessions. sparkApplicationWrite</code></li>
<li><code>dataproc.sessions.terminate</code></li>
</ul>
<p><code>dataproc. workflowTemplates. create</code></p>
<p><code>dataproc. workflowTemplates. delete</code></p>
<p><code>dataproc.workflowTemplates.get</code></p>
<p><code>dataproc. workflowTemplates. instantiate</code></p>
<p><code>dataproc. workflowTemplates. instantiateInline</code></p>
<p><code>dataproc. workflowTemplates. list</code></p>
<p><code>dataproc. workflowTemplates. update</code></p>
<p><code>dataprocrm.nodePools.*</code></p>
<ul>
<li><code>dataprocrm.nodePools.create</code></li>
<li><code>dataprocrm.nodePools.delete</code></li>
<li><code>dataprocrm. nodePools. deleteNodes</code></li>
<li><code>dataprocrm.nodePools.get</code></li>
<li><code>dataprocrm.nodePools.list</code></li>
<li><code>dataprocrm.nodePools.resize</code></li>
</ul>
<p><code>dataprocrm.nodes.get</code></p>
<p><code>dataprocrm.nodes.heartbeat</code></p>
<p><code>dataprocrm.nodes.list</code></p>
<p><code>dataprocrm.nodes.update</code></p>
<p><code>dataprocrm.operations.get</code></p>
<p><code>dataprocrm.operations.list</code></p>
<p><code>dataprocrm.workloads.*</code></p>
<ul>
<li><code>dataprocrm.workloads.cancel</code></li>
<li><code>dataprocrm.workloads.create</code></li>
<li><code>dataprocrm.workloads.delete</code></li>
<li><code>dataprocrm.workloads.get</code></li>
<li><code>dataprocrm.workloads.list</code></li>
</ul>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns. networks. bindPrivateDNSZone</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>networkconnectivity. internalRanges. get</code></p>
<p><code>networkconnectivity. internalRanges. list</code></p>
<p><code>networkconnectivity. locations.*</code></p>
<ul>
<li><code>networkconnectivity. locations. get</code></li>
<li><code>networkconnectivity. locations. list</code></li>
</ul>
<p><code>networkconnectivity. operations. get</code></p>
<p><code>networkconnectivity. operations. list</code></p>
<p><code>networkconnectivity. policyBasedRoutes. get</code></p>
<p><code>networkconnectivity. policyBasedRoutes. list</code></p>
<p><code>networkmanagement. connectivitytests. get</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networksecurity. addressGroups. get</code></p>
<p><code>networksecurity. addressGroups. list</code></p>
<p><code>networksecurity. authorizationPolicies. get</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authzPolicies. get</code></p>
<p><code>networksecurity. authzPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. get</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. firewallEndpointAssociations. get</code></p>
<p><code>networksecurity. firewallEndpointAssociations. list</code></p>
<p><code>networksecurity. firewallEndpoints. get</code></p>
<p><code>networksecurity. firewallEndpoints. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. get</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. get</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. list</code></p>
<p><code>networksecurity.locations.*</code></p>
<ul>
<li><code>networksecurity.locations.get</code></li>
<li><code>networksecurity.locations.list</code></li>
</ul>
<p><code>networksecurity.operations.get</code></p>
<p><code>networksecurity. operations. list</code></p>
<p><code>networksecurity. sacAttachments. get</code></p>
<p><code>networksecurity. sacAttachments. list</code></p>
<p><code>networksecurity.sacRealms.get</code></p>
<p><code>networksecurity.sacRealms.list</code></p>
<p><code>networksecurity. securityProfileGroups. get</code></p>
<p><code>networksecurity. securityProfileGroups. list</code></p>
<p><code>networksecurity. securityProfiles. get</code></p>
<p><code>networksecurity. securityProfiles. list</code></p>
<p><code>networksecurity. serverTlsPolicies. get</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. tlsInspectionPolicies. get</code></p>
<p><code>networksecurity. tlsInspectionPolicies. list</code></p>
<p><code>networksecurity.urlLists.get</code></p>
<p><code>networksecurity.urlLists.list</code></p>
<p><code>networkservices. agentGateways. get</code></p>
<p><code>networkservices. agentGateways. list</code></p>
<p><code>networkservices. authzExtensions. get</code></p>
<p><code>networkservices. authzExtensions. list</code></p>
<p><code>networkservices. endpointPolicies. get</code></p>
<p><code>networkservices. endpointPolicies. list</code></p>
<p><code>networkservices.gateways.get</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices. googleTagGatewayPolicies. get</code></p>
<p><code>networkservices. googleTagGatewayPolicies. list</code></p>
<p><code>networkservices.grpcRoutes.get</code></p>
<p><code>networkservices. grpcRoutes. list</code></p>
<p><code>networkservices. httpFilters. get</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices.httpRoutes.get</code></p>
<p><code>networkservices. httpRoutes. list</code></p>
<p><code>networkservices. httpfilters. get</code></p>
<p><code>networkservices. httpfilters. list</code></p>
<p><code>networkservices. lbEdgeExtensions. get</code></p>
<p><code>networkservices. lbEdgeExtensions. list</code></p>
<p><code>networkservices. lbRouteExtensions. get</code></p>
<p><code>networkservices. lbRouteExtensions. list</code></p>
<p><code>networkservices. lbTrafficExtensions. get</code></p>
<p><code>networkservices. lbTrafficExtensions. list</code></p>
<p><code>networkservices.locations.*</code></p>
<ul>
<li><code>networkservices.locations.get</code></li>
<li><code>networkservices.locations.list</code></li>
</ul>
<p><code>networkservices.meshes.get</code></p>
<p><code>networkservices.meshes.list</code></p>
<p><code>networkservices.operations.get</code></p>
<p><code>networkservices. operations. list</code></p>
<p><code>networkservices.route_views.*</code></p>
<ul>
<li><code>networkservices. route_views. get</code></li>
<li><code>networkservices. route_views. list</code></li>
</ul>
<p><code>networkservices. serviceBindings. get</code></p>
<p><code>networkservices. serviceBindings. list</code></p>
<p><code>networkservices. serviceLbPolicies. get</code></p>
<p><code>networkservices. serviceLbPolicies. list</code></p>
<p><code>networkservices. swpSecurityExtensions. get</code></p>
<p><code>networkservices. swpSecurityExtensions. list</code></p>
<p><code>networkservices.tcpRoutes.get</code></p>
<p><code>networkservices.tcpRoutes.list</code></p>
<p><code>networkservices.tlsRoutes.get</code></p>
<p><code>networkservices.tlsRoutes.list</code></p>
<p><code>networkservices. wasmPlugins. get</code></p>
<p><code>networkservices. wasmPlugins. list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>recommender. iamPolicyInsights.*</code></p>
<ul>
<li><code>recommender. iamPolicyInsights. get</code></li>
<li><code>recommender. iamPolicyInsights. list</code></li>
<li><code>recommender. iamPolicyInsights. update</code></li>
</ul>
<p><code>recommender. iamPolicyRecommendations.*</code></p>
<ul>
<li><code>recommender. iamPolicyRecommendations. get</code></li>
<li><code>recommender. iamPolicyRecommendations. list</code></li>
<li><code>recommender. iamPolicyRecommendations. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteInsights. get</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. list</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteRecommendations. get</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. list</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. update</code></li>
</ul>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicenetworking.services.get</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>spanner.databaseOperations.*</code></p>
<ul>
<li><code>spanner. databaseOperations. cancel</code></li>
<li><code>spanner.databaseOperations.get</code></li>
<li><code>spanner. databaseOperations. list</code></li>
</ul>
<p><code>spanner.databases.adapt</code></p>
<p><code>spanner. databases. beginOrRollbackReadWriteTransaction</code></p>
<p><code>spanner. databases. beginPartitionedDmlTransaction</code></p>
<p><code>spanner. databases. beginReadOnlyTransaction</code></p>
<p><code>spanner.databases.changequorum</code></p>
<p><code>spanner.databases.get</code></p>
<p><code>spanner.databases.getDdl</code></p>
<p><code>spanner.databases.list</code></p>
<p><code>spanner. databases. partitionQuery</code></p>
<p><code>spanner. databases. partitionRead</code></p>
<p><code>spanner.databases.read</code></p>
<p><code>spanner.databases.select</code></p>
<p><code>spanner.databases.updateDdl</code></p>
<p><code>spanner.databases.write</code></p>
<p><code>spanner.instanceConfigs.get</code></p>
<p><code>spanner.instanceConfigs.list</code></p>
<p><code>spanner.instancePartitions.get</code></p>
<p><code>spanner. instancePartitions. list</code></p>
<p><code>spanner.instances.get</code></p>
<p><code>spanner.instances.list</code></p>
<p><code>spanner. instances. listEffectiveTags</code></p>
<p><code>spanner. instances. listTagBindings</code></p>
<p><code>spanner.sessions.*</code></p>
<ul>
<li><code>spanner.sessions.create</code></li>
<li><code>spanner.sessions.delete</code></li>
<li><code>spanner.sessions.get</code></li>
<li><code>spanner.sessions.list</code></li>
</ul>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.anywhereCaches.*</code></p>
<ul>
<li><code>storage.anywhereCaches.create</code></li>
<li><code>storage.anywhereCaches.disable</code></li>
<li><code>storage.anywhereCaches.get</code></li>
<li><code>storage.anywhereCaches.list</code></li>
<li><code>storage.anywhereCaches.pause</code></li>
<li><code>storage.anywhereCaches.resume</code></li>
<li><code>storage.anywhereCaches.update</code></li>
</ul>
<p><code>storage.bucketOperations.*</code></p>
<ul>
<li><code>storage. bucketOperations. cancel</code></li>
<li><code>storage.bucketOperations.get</code></li>
<li><code>storage.bucketOperations.list</code></li>
</ul>
<p><code>storage.buckets.*</code></p>
<ul>
<li><code>storage.buckets.create</code></li>
<li><code>storage. buckets. createTagBinding</code></li>
<li><code>storage.buckets.delete</code></li>
<li><code>storage. buckets. deleteTagBinding</code></li>
<li><code>storage. buckets. enableObjectRetention</code></li>
<li><code>storage.buckets.get</code></li>
<li><code>storage.buckets.getIamPolicy</code></li>
<li><code>storage.buckets.getIpFilter</code></li>
<li><code>storage. buckets. getObjectInsights</code></li>
<li><code>storage.buckets.list</code></li>
<li><code>storage. buckets. listEffectiveTags</code></li>
<li><code>storage. buckets. listTagBindings</code></li>
<li><code>storage.buckets.relocate</code></li>
<li><code>storage.buckets.restore</code></li>
<li><code>storage.buckets.setIamPolicy</code></li>
<li><code>storage.buckets.setIpFilter</code></li>
<li><code>storage.buckets.update</code></li>
<li><code>storage. buckets. viewIntelligenceDetails</code></li>
<li><code>storage. buckets. viewSecurityIntelligenceDetails</code></li>
</ul>
<p><code>storage.featureConfigs.*</code></p>
<ul>
<li><code>storage.featureConfigs.create</code></li>
<li><code>storage.featureConfigs.delete</code></li>
<li><code>storage.featureConfigs.get</code></li>
<li><code>storage.featureConfigs.list</code></li>
<li><code>storage.featureConfigs.update</code></li>
</ul>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.intelligenceConfigs.*</code></p>
<ul>
<li><code>storage. intelligenceConfigs. get</code></li>
<li><code>storage. intelligenceConfigs. update</code></li>
</ul>
<p><code>storage.managedFolders.*</code></p>
<ul>
<li><code>storage.managedFolders.create</code></li>
<li><code>storage.managedFolders.delete</code></li>
<li><code>storage.managedFolders.get</code></li>
<li><code>storage. managedFolders. getIamPolicy</code></li>
<li><code>storage.managedFolders.list</code></li>
<li><code>storage. managedFolders. setIamPolicy</code></li>
<li><code>storage.managedFolders.update</code></li>
</ul>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.*</code></p>
<ul>
<li><code>storage.objects.create</code></li>
<li><code>storage.objects.createContext</code></li>
<li><code>storage.objects.delete</code></li>
<li><code>storage.objects.deleteContext</code></li>
<li><code>storage.objects.get</code></li>
<li><code>storage.objects.getIamPolicy</code></li>
<li><code>storage.objects.list</code></li>
<li><code>storage.objects.move</code></li>
<li><code>storage. objects. overrideUnlockedRetention</code></li>
<li><code>storage.objects.restore</code></li>
<li><code>storage.objects.setIamPolicy</code></li>
<li><code>storage.objects.setRetention</code></li>
<li><code>storage.objects.update</code></li>
<li><code>storage.objects.updateContext</code></li>
</ul>
<p><code>storagebatchoperations.*</code></p>
<ul>
<li><code>storagebatchoperations. bucketOperations. get</code></li>
<li><code>storagebatchoperations. bucketOperations. list</code></li>
<li><code>storagebatchoperations. jobs. cancel</code></li>
<li><code>storagebatchoperations. jobs. create</code></li>
<li><code>storagebatchoperations. jobs. delete</code></li>
<li><code>storagebatchoperations. jobs. get</code></li>
<li><code>storagebatchoperations. jobs. list</code></li>
<li><code>storagebatchoperations. locations. get</code></li>
<li><code>storagebatchoperations. locations. list</code></li>
<li><code>storagebatchoperations. operations. cancel</code></li>
<li><code>storagebatchoperations. operations. delete</code></li>
<li><code>storagebatchoperations. operations. get</code></li>
<li><code>storagebatchoperations. operations. list</code></li>
</ul>
<p><code>trafficdirector.*</code></p>
<ul>
<li><code>trafficdirector. networks. getConfigs</code></li>
<li><code>trafficdirector. networks. reportMetrics</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Cloud Data Fusion permissions

| Permission                                         | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `datafusion.artifacts.create`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.artifacts.delete`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.artifacts.get`                         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion.artifacts.list`                        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.artifacts.update`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.instances.create`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion. instances. createTagBinding`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `datafusion.instances.delete`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion. instances. deleteTagBinding`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `datafusion.instances.get`                         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Accessor](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor) ( `roles/ datafusion.accessor` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion. instances. getIamPolicy`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Accessor](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor) ( `roles/ datafusion.accessor` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                   |
| `datafusion.instances.list`                        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Accessor](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor) ( `roles/ datafusion.accessor` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                   |
| `datafusion. instances. listEffectiveTags`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [Tag Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer) ( `roles/ resourcemanager.tagViewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Accessor](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor) ( `roles/ datafusion.accessor` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `datafusion. instances. listTagBindings`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [Tag Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer) ( `roles/ resourcemanager.tagViewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Accessor](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor) ( `roles/ datafusion.accessor` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `datafusion.instances.restart`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.instances.runtime`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.runner) ( `roles/ datafusion.runner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. instances. setIamPolicy`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `datafusion.instances.update`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.instances.upgrade`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.locations.get`                         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion.locations.list`                        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.namespaces.create`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.namespaces.delete`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.namespaces.get`                        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion. namespaces. getIamPolicy`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.namespaces.list`                       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. namespaces. provisionCredential`      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. namespaces. readRepository`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. namespaces. setIamPolicy`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `datafusion. namespaces. setServiceAccount`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion. namespaces. unsetServiceAccount`      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.namespaces.update`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. namespaces. updateRepositoryMetadata` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion. namespaces. writeRepository`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.operations.cancel`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.operations.delete`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion.operations.get`                        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion.operations.list`                       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. pipelineConnections. create`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion. pipelineConnections. delete`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion. pipelineConnections. get`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion. pipelineConnections. list`            | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. pipelineConnections. update`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `datafusion. pipelineConnections. use`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.pipelines.create`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.pipelines.delete`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.pipelines.execute`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.pipelines.get`                         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion.pipelines.list`                        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.pipelines.preview`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `datafusion.pipelines.update`                      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.profiles.create`                       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.profiles.delete`                       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.profiles.get`                          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `datafusion.profiles.list`                         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.profiles.update`                       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `datafusion.secureKeys.create`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.secureKeys.delete`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion. secureKeys. getSecret`                | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.secureKeys.list`                       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Cloud Data Fusion Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer) ( `roles/ datafusion.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `datafusion.secureKeys.update`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Data Fusion Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin) ( `roles/ datafusion.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Data Fusion Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer) ( `roles/ datafusion.developer` ) [Cloud Data Fusion Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator) ( `roles/ datafusion.operator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
