---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dataflow
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow
title: Dataflow roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dataflow. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dataflow roles

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
<td>Dataflow Admin
<p>( <code>roles/ dataflow.admin</code> )</p>
<p>Minimal role for creating and managing dataflow jobs.</p></td>
<td><p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.builds.update</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>compute.machineTypes.get</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regions.list</code></p>
<p><code>compute.zones.list</code></p>
<p><code>dataflow.jobs.*</code></p>
<ul>
<li><code>dataflow.jobs.cancel</code></li>
<li><code>dataflow.jobs.create</code></li>
<li><code>dataflow.jobs.get</code></li>
<li><code>dataflow.jobs.list</code></li>
<li><code>dataflow.jobs.snapshot</code></li>
<li><code>dataflow.jobs.updateContents</code></li>
</ul>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.metrics.get</code></p>
<p><code>dataflow.snapshots.*</code></p>
<ul>
<li><code>dataflow.snapshots.delete</code></li>
<li><code>dataflow.snapshots.get</code></li>
<li><code>dataflow.snapshots.list</code></li>
</ul>
<p><code>recommender. dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code>recommender. dataflowDiagnosticsInsights. get</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. list</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. update</code></li>
</ul>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataflow Viewer
<p>( <code>roles/ dataflow.viewer</code> )</p>
<p>Provides read-only access to all Dataflow-related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>dataflow.jobs.get</code></p>
<p><code>dataflow.jobs.list</code></p>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.metrics.get</code></p>
<p><code>dataflow.snapshots.get</code></p>
<p><code>dataflow.snapshots.list</code></p>
<p><code>recommender. dataflowDiagnosticsInsights. get</code></p>
<p><code>recommender. dataflowDiagnosticsInsights. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataflow Developer
<p>( <code>roles/ dataflow.developer</code> )</p>
<p>Provides the permissions necessary to execute and manipulate Dataflow jobs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.builds.update</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regions.list</code></p>
<p><code>compute.zones.list</code></p>
<p><code>dataflow.jobs.*</code></p>
<ul>
<li><code>dataflow.jobs.cancel</code></li>
<li><code>dataflow.jobs.create</code></li>
<li><code>dataflow.jobs.get</code></li>
<li><code>dataflow.jobs.list</code></li>
<li><code>dataflow.jobs.snapshot</code></li>
<li><code>dataflow.jobs.updateContents</code></li>
</ul>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.metrics.get</code></p>
<p><code>dataflow.snapshots.*</code></p>
<ul>
<li><code>dataflow.snapshots.delete</code></li>
<li><code>dataflow.snapshots.get</code></li>
<li><code>dataflow.snapshots.list</code></li>
</ul>
<p><code>recommender. dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code>recommender. dataflowDiagnosticsInsights. get</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. list</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. update</code></li>
</ul>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataflow Worker
<p>( <code>roles/ dataflow.worker</code> )</p>
<p>Provides the permissions necessary for a Compute Engine service account to execute work units for a Dataflow pipeline.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>autoscaling. sites. readRecommendations</code></p>
<p><code>autoscaling.sites.writeMetrics</code></p>
<p><code>autoscaling.sites.writeState</code></p>
<p><code>compute. instanceGroupManagers. update</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute. instances. setDiskAutoDelete</code></p>
<p><code>dataflow.jobs.get</code></p>
<p><code>dataflow.shuffle.*</code></p>
<ul>
<li><code>dataflow.shuffle.read</code></li>
<li><code>dataflow.shuffle.write</code></li>
</ul>
<p><code>dataflow.streamingWorkItems.*</code></p>
<ul>
<li><code>dataflow. streamingWorkItems. ImportState</code></li>
<li><code>dataflow. streamingWorkItems. commitWork</code></li>
<li><code>dataflow. streamingWorkItems. getData</code></li>
<li><code>dataflow. streamingWorkItems. getWork</code></li>
<li><code>dataflow. streamingWorkItems. getWorkerMetadata</code></li>
</ul>
<p><code>dataflow.workItems.*</code></p>
<ul>
<li><code>dataflow.workItems.lease</code></li>
<li><code>dataflow.workItems.sendMessage</code></li>
<li><code>dataflow.workItems.update</code></li>
</ul>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p></td>
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
<td>Cloud Dataflow Service Agent
<p>( <code>roles/ dataflow.serviceAgent</code> )</p>
<p>Gives Cloud Dataflow service account access to managed resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>backupdr. backupPlanAssociations. createForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. getForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></p>
<p><code>backupdr.backupPlans.get</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr. backupPlans. useForComputeDisk</code></p>
<p><code>backupdr. backupPlans. useForComputeInstance</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr. serviceConfig. initialize</code></p>
<p><code>bigquery.bireservations.*</code></p>
<ul>
<li><code>bigquery.bireservations.get</code></li>
<li><code>bigquery.bireservations.update</code></li>
</ul>
<p><code>bigquery.capacityCommitments.*</code></p>
<ul>
<li><code>bigquery. capacityCommitments. create</code></li>
<li><code>bigquery. capacityCommitments. delete</code></li>
<li><code>bigquery. capacityCommitments. get</code></li>
<li><code>bigquery. capacityCommitments. list</code></li>
<li><code>bigquery. capacityCommitments. update</code></li>
</ul>
<p><code>bigquery.config.*</code></p>
<ul>
<li><code>bigquery.config.get</code></li>
<li><code>bigquery.config.update</code></li>
</ul>
<p><code>bigquery.connections.*</code></p>
<ul>
<li><code>bigquery.connections.create</code></li>
<li><code>bigquery.connections.delegate</code></li>
<li><code>bigquery.connections.delete</code></li>
<li><code>bigquery.connections.get</code></li>
<li><code>bigquery. connections. getIamPolicy</code></li>
<li><code>bigquery.connections.list</code></li>
<li><code>bigquery. connections. setIamPolicy</code></li>
<li><code>bigquery.connections.update</code></li>
<li><code>bigquery.connections.updateTag</code></li>
<li><code>bigquery.connections.use</code></li>
</ul>
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
<p><code>bigquery.jobs.*</code></p>
<ul>
<li><code>bigquery.jobs.create</code></li>
<li><code>bigquery. jobs. createGlobalQuery</code></li>
<li><code>bigquery.jobs.delete</code></li>
<li><code>bigquery.jobs.get</code></li>
<li><code>bigquery.jobs.list</code></li>
<li><code>bigquery.jobs.listAll</code></li>
<li><code>bigquery. jobs. listExecutionMetadata</code></li>
<li><code>bigquery.jobs.update</code></li>
</ul>
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
<p><code>bigquery.objectRefs.*</code></p>
<ul>
<li><code>bigquery.objectRefs.read</code></li>
<li><code>bigquery.objectRefs.write</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.readsessions.*</code></p>
<ul>
<li><code>bigquery.readsessions.create</code></li>
<li><code>bigquery.readsessions.getData</code></li>
<li><code>bigquery.readsessions.update</code></li>
</ul>
<p><code>bigquery. reservationAssignments.*</code></p>
<ul>
<li><code>bigquery. reservationAssignments. create</code></li>
<li><code>bigquery. reservationAssignments. delete</code></li>
<li><code>bigquery. reservationAssignments. list</code></li>
<li><code>bigquery. reservationAssignments. search</code></li>
</ul>
<p><code>bigquery.reservationGroups.*</code></p>
<ul>
<li><code>bigquery. reservationGroups. create</code></li>
<li><code>bigquery. reservationGroups. delete</code></li>
<li><code>bigquery.reservationGroups.get</code></li>
<li><code>bigquery. reservationGroups. list</code></li>
<li><code>bigquery. reservationGroups. update</code></li>
</ul>
<p><code>bigquery.reservations.*</code></p>
<ul>
<li><code>bigquery.reservations.create</code></li>
<li><code>bigquery.reservations.delete</code></li>
<li><code>bigquery.reservations.get</code></li>
<li><code>bigquery. reservations. getIamPolicy</code></li>
<li><code>bigquery.reservations.list</code></li>
<li><code>bigquery. reservations. listFailoverDatasets</code></li>
<li><code>bigquery. reservations. setIamPolicy</code></li>
<li><code>bigquery.reservations.update</code></li>
<li><code>bigquery.reservations.use</code></li>
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
<p><code>bigquery. rowAccessPolicies. overrideTimeTravelRestrictions</code></p>
<p><code>bigquery. rowAccessPolicies. setIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. update</code></p>
<p><code>bigquery.savedqueries.*</code></p>
<ul>
<li><code>bigquery.savedqueries.create</code></li>
<li><code>bigquery.savedqueries.delete</code></li>
<li><code>bigquery.savedqueries.get</code></li>
<li><code>bigquery.savedqueries.list</code></li>
<li><code>bigquery.savedqueries.update</code></li>
</ul>
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
<p><code>bigquery.transfers.*</code></p>
<ul>
<li><code>bigquery.transfers.get</code></li>
<li><code>bigquery.transfers.update</code></li>
</ul>
<p><code>bigquerymigration. translation. translate</code></p>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>clouddebugger.breakpoints.list</code></p>
<p><code>clouddebugger. breakpoints. listActive</code></p>
<p><code>clouddebugger. breakpoints. update</code></p>
<p><code>clouddebugger.debuggees.create</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute.addresses.*</code></p>
<ul>
<li><code>compute.addresses.create</code></li>
<li><code>compute. addresses. createInternal</code></li>
<li><code>compute. addresses. createTagBinding</code></li>
<li><code>compute.addresses.delete</code></li>
<li><code>compute. addresses. deleteInternal</code></li>
<li><code>compute. addresses. deleteTagBinding</code></li>
<li><code>compute.addresses.get</code></li>
<li><code>compute.addresses.list</code></li>
<li><code>compute. addresses. listEffectiveTags</code></li>
<li><code>compute. addresses. listTagBindings</code></li>
<li><code>compute.addresses.setLabels</code></li>
<li><code>compute.addresses.use</code></li>
<li><code>compute.addresses.useInternal</code></li>
</ul>
<p><code>compute.autoscalers.*</code></p>
<ul>
<li><code>compute.autoscalers.create</code></li>
<li><code>compute.autoscalers.delete</code></li>
<li><code>compute.autoscalers.get</code></li>
<li><code>compute.autoscalers.list</code></li>
<li><code>compute.autoscalers.update</code></li>
</ul>
<p><code>compute.backendBuckets.*</code></p>
<ul>
<li><code>compute. backendBuckets. addSignedUrlKey</code></li>
<li><code>compute.backendBuckets.create</code></li>
<li><code>compute. backendBuckets. createTagBinding</code></li>
<li><code>compute.backendBuckets.delete</code></li>
<li><code>compute. backendBuckets. deleteSignedUrlKey</code></li>
<li><code>compute. backendBuckets. deleteTagBinding</code></li>
<li><code>compute.backendBuckets.get</code></li>
<li><code>compute. backendBuckets. getIamPolicy</code></li>
<li><code>compute.backendBuckets.list</code></li>
<li><code>compute. backendBuckets. listEffectiveTags</code></li>
<li><code>compute. backendBuckets. listTagBindings</code></li>
<li><code>compute. backendBuckets. setIamPolicy</code></li>
<li><code>compute. backendBuckets. setSecurityPolicy</code></li>
<li><code>compute.backendBuckets.update</code></li>
<li><code>compute.backendBuckets.use</code></li>
</ul>
<p><code>compute.backendServices.*</code></p>
<ul>
<li><code>compute. backendServices. addSignedUrlKey</code></li>
<li><code>compute.backendServices.create</code></li>
<li><code>compute. backendServices. createTagBinding</code></li>
<li><code>compute.backendServices.delete</code></li>
<li><code>compute. backendServices. deleteSignedUrlKey</code></li>
<li><code>compute. backendServices. deleteTagBinding</code></li>
<li><code>compute.backendServices.get</code></li>
<li><code>compute. backendServices. getIamPolicy</code></li>
<li><code>compute.backendServices.list</code></li>
<li><code>compute. backendServices. listEffectiveTags</code></li>
<li><code>compute. backendServices. listTagBindings</code></li>
<li><code>compute. backendServices. setIamPolicy</code></li>
<li><code>compute. backendServices. setSecurityPolicy</code></li>
<li><code>compute.backendServices.update</code></li>
<li><code>compute.backendServices.use</code></li>
</ul>
<p><code>compute.crossSiteNetworks.*</code></p>
<ul>
<li><code>compute. crossSiteNetworks. create</code></li>
<li><code>compute. crossSiteNetworks. delete</code></li>
<li><code>compute.crossSiteNetworks.get</code></li>
<li><code>compute.crossSiteNetworks.list</code></li>
<li><code>compute. crossSiteNetworks. update</code></li>
</ul>
<p><code>compute.diskSettings.*</code></p>
<ul>
<li><code>compute.diskSettings.get</code></li>
<li><code>compute.diskSettings.update</code></li>
</ul>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.*</code></p>
<ul>
<li><code>compute. disks. addResourcePolicies</code></li>
<li><code>compute.disks.create</code></li>
<li><code>compute.disks.createSnapshot</code></li>
<li><code>compute.disks.createTagBinding</code></li>
<li><code>compute.disks.delete</code></li>
<li><code>compute.disks.deleteTagBinding</code></li>
<li><code>compute.disks.get</code></li>
<li><code>compute.disks.getIamPolicy</code></li>
<li><code>compute.disks.list</code></li>
<li><code>compute. disks. listEffectiveTags</code></li>
<li><code>compute.disks.listTagBindings</code></li>
<li><code>compute. disks. removeResourcePolicies</code></li>
<li><code>compute.disks.resize</code></li>
<li><code>compute.disks.setIamPolicy</code></li>
<li><code>compute.disks.setLabels</code></li>
<li><code>compute. disks. startAsyncReplication</code></li>
<li><code>compute. disks. stopAsyncReplication</code></li>
<li><code>compute. disks. stopGroupAsyncReplication</code></li>
<li><code>compute.disks.update</code></li>
<li><code>compute.disks.updateKmsKey</code></li>
<li><code>compute.disks.use</code></li>
<li><code>compute.disks.useReadOnly</code></li>
</ul>
<p><code>compute.externalVpnGateways.*</code></p>
<ul>
<li><code>compute. externalVpnGateways. create</code></li>
<li><code>compute. externalVpnGateways. createTagBinding</code></li>
<li><code>compute. externalVpnGateways. delete</code></li>
<li><code>compute. externalVpnGateways. deleteTagBinding</code></li>
<li><code>compute. externalVpnGateways. get</code></li>
<li><code>compute. externalVpnGateways. list</code></li>
<li><code>compute. externalVpnGateways. listEffectiveTags</code></li>
<li><code>compute. externalVpnGateways. listTagBindings</code></li>
<li><code>compute. externalVpnGateways. setLabels</code></li>
<li><code>compute. externalVpnGateways. use</code></li>
</ul>
<p><code>compute.firewallPolicies.get</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute.firewallPolicies.use</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.forwardingRules.*</code></p>
<ul>
<li><code>compute.forwardingRules.create</code></li>
<li><code>compute. forwardingRules. createTagBinding</code></li>
<li><code>compute.forwardingRules.delete</code></li>
<li><code>compute. forwardingRules. deleteTagBinding</code></li>
<li><code>compute.forwardingRules.get</code></li>
<li><code>compute.forwardingRules.list</code></li>
<li><code>compute. forwardingRules. listEffectiveTags</code></li>
<li><code>compute. forwardingRules. listTagBindings</code></li>
<li><code>compute. forwardingRules. pscCreate</code></li>
<li><code>compute. forwardingRules. pscDelete</code></li>
<li><code>compute. forwardingRules. pscSetLabels</code></li>
<li><code>compute. forwardingRules. pscUpdate</code></li>
<li><code>compute. forwardingRules. setLabels</code></li>
<li><code>compute. forwardingRules. setTarget</code></li>
<li><code>compute.forwardingRules.update</code></li>
<li><code>compute.forwardingRules.use</code></li>
</ul>
<p><code>compute.globalAddresses.*</code></p>
<ul>
<li><code>compute.globalAddresses.create</code></li>
<li><code>compute. globalAddresses. createInternal</code></li>
<li><code>compute. globalAddresses. createTagBinding</code></li>
<li><code>compute.globalAddresses.delete</code></li>
<li><code>compute. globalAddresses. deleteInternal</code></li>
<li><code>compute. globalAddresses. deleteTagBinding</code></li>
<li><code>compute.globalAddresses.get</code></li>
<li><code>compute.globalAddresses.list</code></li>
<li><code>compute. globalAddresses. listEffectiveTags</code></li>
<li><code>compute. globalAddresses. listTagBindings</code></li>
<li><code>compute. globalAddresses. setLabels</code></li>
<li><code>compute.globalAddresses.use</code></li>
</ul>
<p><code>compute. globalForwardingRules.*</code></p>
<ul>
<li><code>compute. globalForwardingRules. create</code></li>
<li><code>compute. globalForwardingRules. createTagBinding</code></li>
<li><code>compute. globalForwardingRules. delete</code></li>
<li><code>compute. globalForwardingRules. deleteTagBinding</code></li>
<li><code>compute. globalForwardingRules. get</code></li>
<li><code>compute. globalForwardingRules. list</code></li>
<li><code>compute. globalForwardingRules. listEffectiveTags</code></li>
<li><code>compute. globalForwardingRules. listTagBindings</code></li>
<li><code>compute. globalForwardingRules. pscCreate</code></li>
<li><code>compute. globalForwardingRules. pscDelete</code></li>
<li><code>compute. globalForwardingRules. pscSetLabels</code></li>
<li><code>compute. globalForwardingRules. pscUpdate</code></li>
<li><code>compute. globalForwardingRules. setLabels</code></li>
<li><code>compute. globalForwardingRules. setTarget</code></li>
<li><code>compute. globalForwardingRules. update</code></li>
</ul>
<p><code>compute. globalFrontendSettings.*</code></p>
<ul>
<li><code>compute. globalFrontendSettings. get</code></li>
<li><code>compute. globalFrontendSettings. update</code></li>
</ul>
<p><code>compute. globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. create</code></li>
<li><code>compute. globalNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. delete</code></li>
<li><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. get</code></li>
<li><code>compute. globalNetworkEndpointGroups. list</code></li>
<li><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. globalNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. globalNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. delete</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. get</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. list</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. updatePolicy</code></p>
<p><code>compute.healthChecks.*</code></p>
<ul>
<li><code>compute.healthChecks.create</code></li>
<li><code>compute. healthChecks. createTagBinding</code></li>
<li><code>compute.healthChecks.delete</code></li>
<li><code>compute. healthChecks. deleteTagBinding</code></li>
<li><code>compute.healthChecks.get</code></li>
<li><code>compute.healthChecks.list</code></li>
<li><code>compute. healthChecks. listEffectiveTags</code></li>
<li><code>compute. healthChecks. listTagBindings</code></li>
<li><code>compute.healthChecks.update</code></li>
<li><code>compute.healthChecks.use</code></li>
<li><code>compute. healthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.hosts.*</code></p>
<ul>
<li><code>compute.hosts.get</code></li>
<li><code>compute.hosts.getVersion</code></li>
<li><code>compute.hosts.list</code></li>
</ul>
<p><code>compute.httpHealthChecks.*</code></p>
<ul>
<li><code>compute. httpHealthChecks. create</code></li>
<li><code>compute. httpHealthChecks. createTagBinding</code></li>
<li><code>compute. httpHealthChecks. delete</code></li>
<li><code>compute. httpHealthChecks. deleteTagBinding</code></li>
<li><code>compute.httpHealthChecks.get</code></li>
<li><code>compute.httpHealthChecks.list</code></li>
<li><code>compute. httpHealthChecks. listEffectiveTags</code></li>
<li><code>compute. httpHealthChecks. listTagBindings</code></li>
<li><code>compute. httpHealthChecks. update</code></li>
<li><code>compute.httpHealthChecks.use</code></li>
<li><code>compute. httpHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.httpsHealthChecks.*</code></p>
<ul>
<li><code>compute. httpsHealthChecks. create</code></li>
<li><code>compute. httpsHealthChecks. createTagBinding</code></li>
<li><code>compute. httpsHealthChecks. delete</code></li>
<li><code>compute. httpsHealthChecks. deleteTagBinding</code></li>
<li><code>compute.httpsHealthChecks.get</code></li>
<li><code>compute.httpsHealthChecks.list</code></li>
<li><code>compute. httpsHealthChecks. listEffectiveTags</code></li>
<li><code>compute. httpsHealthChecks. listTagBindings</code></li>
<li><code>compute. httpsHealthChecks. update</code></li>
<li><code>compute.httpsHealthChecks.use</code></li>
<li><code>compute. httpsHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.images.*</code></p>
<ul>
<li><code>compute.images.create</code></li>
<li><code>compute. images. createTagBinding</code></li>
<li><code>compute.images.delete</code></li>
<li><code>compute. images. deleteTagBinding</code></li>
<li><code>compute.images.deprecate</code></li>
<li><code>compute.images.get</code></li>
<li><code>compute.images.getFromFamily</code></li>
<li><code>compute.images.getIamPolicy</code></li>
<li><code>compute.images.list</code></li>
<li><code>compute. images. listEffectiveTags</code></li>
<li><code>compute.images.listTagBindings</code></li>
<li><code>compute.images.setIamPolicy</code></li>
<li><code>compute.images.setLabels</code></li>
<li><code>compute.images.update</code></li>
<li><code>compute.images.useReadOnly</code></li>
</ul>
<p><code>compute. instanceGroupManagers.*</code></p>
<ul>
<li><code>compute. instanceGroupManagers. create</code></li>
<li><code>compute. instanceGroupManagers. createTagBinding</code></li>
<li><code>compute. instanceGroupManagers. delete</code></li>
<li><code>compute. instanceGroupManagers. deleteTagBinding</code></li>
<li><code>compute. instanceGroupManagers. get</code></li>
<li><code>compute. instanceGroupManagers. list</code></li>
<li><code>compute. instanceGroupManagers. listEffectiveTags</code></li>
<li><code>compute. instanceGroupManagers. listTagBindings</code></li>
<li><code>compute. instanceGroupManagers. update</code></li>
<li><code>compute. instanceGroupManagers. use</code></li>
</ul>
<p><code>compute.instanceGroups.*</code></p>
<ul>
<li><code>compute.instanceGroups.create</code></li>
<li><code>compute. instanceGroups. createTagBinding</code></li>
<li><code>compute.instanceGroups.delete</code></li>
<li><code>compute. instanceGroups. deleteTagBinding</code></li>
<li><code>compute.instanceGroups.get</code></li>
<li><code>compute.instanceGroups.list</code></li>
<li><code>compute. instanceGroups. listEffectiveTags</code></li>
<li><code>compute. instanceGroups. listTagBindings</code></li>
<li><code>compute.instanceGroups.update</code></li>
<li><code>compute.instanceGroups.use</code></li>
</ul>
<p><code>compute.instanceSettings.get</code></p>
<p><code>compute.instanceTemplates.*</code></p>
<ul>
<li><code>compute. instanceTemplates. create</code></li>
<li><code>compute. instanceTemplates. delete</code></li>
<li><code>compute.instanceTemplates.get</code></li>
<li><code>compute. instanceTemplates. getIamPolicy</code></li>
<li><code>compute.instanceTemplates.list</code></li>
<li><code>compute. instanceTemplates. setIamPolicy</code></li>
<li><code>compute. instanceTemplates. useReadOnly</code></li>
</ul>
<p><code>compute.instances.*</code></p>
<ul>
<li><code>compute. instances. addAccessConfig</code></li>
<li><code>compute. instances. addNetworkInterface</code></li>
<li><code>compute. instances. addResourcePolicies</code></li>
<li><code>compute.instances.attachDisk</code></li>
<li><code>compute.instances.create</code></li>
<li><code>compute. instances. createTagBinding</code></li>
<li><code>compute.instances.delete</code></li>
<li><code>compute. instances. deleteAccessConfig</code></li>
<li><code>compute. instances. deleteNetworkInterface</code></li>
<li><code>compute. instances. deleteTagBinding</code></li>
<li><code>compute.instances.detachDisk</code></li>
<li><code>compute.instances.get</code></li>
<li><code>compute. instances. getEffectiveFirewalls</code></li>
<li><code>compute. instances. getGuestAttributes</code></li>
<li><code>compute.instances.getIamPolicy</code></li>
<li><code>compute. instances. getScreenshot</code></li>
<li><code>compute. instances. getSerialPortOutput</code></li>
<li><code>compute. instances. getShieldedInstanceIdentity</code></li>
<li><code>compute. instances. getShieldedVmIdentity</code></li>
<li><code>compute. instances. getVmExtensionState</code></li>
<li><code>compute.instances.list</code></li>
<li><code>compute. instances. listEffectiveTags</code></li>
<li><code>compute. instances. listReferrers</code></li>
<li><code>compute. instances. listTagBindings</code></li>
<li><code>compute. instances. listVmExtensionStates</code></li>
<li><code>compute.instances.osAdminLogin</code></li>
<li><code>compute.instances.osLogin</code></li>
<li><code>compute. instances. pscInterfaceCreate</code></li>
<li><code>compute. instances. removeResourcePolicies</code></li>
<li><code>compute.instances.reset</code></li>
<li><code>compute.instances.resume</code></li>
<li><code>compute. instances. sendDiagnosticInterrupt</code></li>
<li><code>compute. instances. setDeletionProtection</code></li>
<li><code>compute. instances. setDiskAutoDelete</code></li>
<li><code>compute.instances.setIamPolicy</code></li>
<li><code>compute.instances.setLabels</code></li>
<li><code>compute. instances. setMachineResources</code></li>
<li><code>compute. instances. setMachineType</code></li>
<li><code>compute.instances.setMetadata</code></li>
<li><code>compute. instances. setMinCpuPlatform</code></li>
<li><code>compute.instances.setName</code></li>
<li><code>compute. instances. setScheduling</code></li>
<li><code>compute. instances. setSecurityPolicy</code></li>
<li><code>compute. instances. setServiceAccount</code></li>
<li><code>compute. instances. setShieldedInstanceIntegrityPolicy</code></li>
<li><code>compute. instances. setShieldedVmIntegrityPolicy</code></li>
<li><code>compute.instances.setTags</code></li>
<li><code>compute. instances. simulateMaintenanceEvent</code></li>
<li><code>compute.instances.start</code></li>
<li><code>compute. instances. startWithEncryptionKey</code></li>
<li><code>compute.instances.stop</code></li>
<li><code>compute.instances.suspend</code></li>
<li><code>compute.instances.troubleshoot</code></li>
<li><code>compute.instances.update</code></li>
<li><code>compute. instances. updateAccessConfig</code></li>
<li><code>compute. instances. updateDisplayDevice</code></li>
<li><code>compute. instances. updateNetworkInterface</code></li>
<li><code>compute. instances. updateSecurity</code></li>
<li><code>compute. instances. updateShieldedInstanceConfig</code></li>
<li><code>compute. instances. updateShieldedVmConfig</code></li>
<li><code>compute.instances.use</code></li>
<li><code>compute.instances.useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshotGroups.*</code></p>
<ul>
<li><code>compute. instantSnapshotGroups. create</code></li>
<li><code>compute. instantSnapshotGroups. delete</code></li>
<li><code>compute. instantSnapshotGroups. get</code></li>
<li><code>compute. instantSnapshotGroups. getIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. list</code></li>
<li><code>compute. instantSnapshotGroups. setIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshots. create</code></p>
<p><code>compute. instantSnapshots. delete</code></p>
<p><code>compute. instantSnapshots. export</code></p>
<p><code>compute.instantSnapshots.get</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. instantSnapshots. setIamPolicy</code></p>
<p><code>compute. instantSnapshots. setLabels</code></p>
<p><code>compute. instantSnapshots. useReadOnly</code></p>
<p><code>compute. interconnectAttachmentGroups.*</code></p>
<ul>
<li><code>compute. interconnectAttachmentGroups. create</code></li>
<li><code>compute. interconnectAttachmentGroups. delete</code></li>
<li><code>compute. interconnectAttachmentGroups. get</code></li>
<li><code>compute. interconnectAttachmentGroups. list</code></li>
<li><code>compute. interconnectAttachmentGroups. patch</code></li>
</ul>
<p><code>compute. interconnectAttachments.*</code></p>
<ul>
<li><code>compute. interconnectAttachments. create</code></li>
<li><code>compute. interconnectAttachments. createTagBinding</code></li>
<li><code>compute. interconnectAttachments. delete</code></li>
<li><code>compute. interconnectAttachments. deleteTagBinding</code></li>
<li><code>compute. interconnectAttachments. get</code></li>
<li><code>compute. interconnectAttachments. list</code></li>
<li><code>compute. interconnectAttachments. listEffectiveTags</code></li>
<li><code>compute. interconnectAttachments. listTagBindings</code></li>
<li><code>compute. interconnectAttachments. setLabels</code></li>
<li><code>compute. interconnectAttachments. update</code></li>
<li><code>compute. interconnectAttachments. use</code></li>
</ul>
<p><code>compute.interconnectGroups.*</code></p>
<ul>
<li><code>compute. interconnectGroups. create</code></li>
<li><code>compute. interconnectGroups. delete</code></li>
<li><code>compute.interconnectGroups.get</code></li>
<li><code>compute. interconnectGroups. list</code></li>
<li><code>compute. interconnectGroups. patch</code></li>
</ul>
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
<p><code>compute.interconnects.*</code></p>
<ul>
<li><code>compute.interconnects.create</code></li>
<li><code>compute. interconnects. createTagBinding</code></li>
<li><code>compute.interconnects.delete</code></li>
<li><code>compute. interconnects. deleteTagBinding</code></li>
<li><code>compute.interconnects.get</code></li>
<li><code>compute. interconnects. getMacsecConfig</code></li>
<li><code>compute.interconnects.list</code></li>
<li><code>compute. interconnects. listEffectiveTags</code></li>
<li><code>compute. interconnects. listTagBindings</code></li>
<li><code>compute. interconnects. setLabels</code></li>
<li><code>compute.interconnects.setName</code></li>
<li><code>compute.interconnects.update</code></li>
<li><code>compute.interconnects.use</code></li>
</ul>
<p><code>compute.licenseCodes.*</code></p>
<ul>
<li><code>compute.licenseCodes.get</code></li>
<li><code>compute. licenseCodes. getIamPolicy</code></li>
<li><code>compute.licenseCodes.list</code></li>
<li><code>compute. licenseCodes. setIamPolicy</code></li>
</ul>
<p><code>compute.licenses.create</code></p>
<p><code>compute.licenses.delete</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute.licenses.setIamPolicy</code></p>
<p><code>compute.licenses.update</code></p>
<p><code>compute.machineImages.*</code></p>
<ul>
<li><code>compute.machineImages.create</code></li>
<li><code>compute. machineImages. createTagBinding</code></li>
<li><code>compute.machineImages.delete</code></li>
<li><code>compute. machineImages. deleteTagBinding</code></li>
<li><code>compute.machineImages.get</code></li>
<li><code>compute. machineImages. getIamPolicy</code></li>
<li><code>compute.machineImages.list</code></li>
<li><code>compute. machineImages. listEffectiveTags</code></li>
<li><code>compute. machineImages. listTagBindings</code></li>
<li><code>compute. machineImages. setIamPolicy</code></li>
<li><code>compute. machineImages. setLabels</code></li>
<li><code>compute. machineImages. useReadOnly</code></li>
</ul>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.multiMig.*</code></p>
<ul>
<li><code>compute.multiMig.create</code></li>
<li><code>compute.multiMig.delete</code></li>
<li><code>compute.multiMig.get</code></li>
<li><code>compute.multiMig.list</code></li>
</ul>
<p><code>compute.multiMigMembers.*</code></p>
<ul>
<li><code>compute.multiMigMembers.get</code></li>
<li><code>compute.multiMigMembers.list</code></li>
</ul>
<p><code>compute.networkAttachments.*</code></p>
<ul>
<li><code>compute. networkAttachments. create</code></li>
<li><code>compute. networkAttachments. createTagBinding</code></li>
<li><code>compute. networkAttachments. delete</code></li>
<li><code>compute. networkAttachments. deleteTagBinding</code></li>
<li><code>compute.networkAttachments.get</code></li>
<li><code>compute. networkAttachments. getIamPolicy</code></li>
<li><code>compute. networkAttachments. list</code></li>
<li><code>compute. networkAttachments. listEffectiveTags</code></li>
<li><code>compute. networkAttachments. listTagBindings</code></li>
<li><code>compute. networkAttachments. setIamPolicy</code></li>
<li><code>compute. networkAttachments. update</code></li>
<li><code>compute.networkAttachments.use</code></li>
</ul>
<p><code>compute. networkEndpointGroups.*</code></p>
<ul>
<li><code>compute. networkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. create</code></li>
<li><code>compute. networkEndpointGroups. createTagBinding</code></li>
<li><code>compute. networkEndpointGroups. delete</code></li>
<li><code>compute. networkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. networkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. get</code></li>
<li><code>compute. networkEndpointGroups. list</code></li>
<li><code>compute. networkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. networkEndpointGroups. listTagBindings</code></li>
<li><code>compute. networkEndpointGroups. use</code></li>
</ul>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.*</code></p>
<ul>
<li><code>compute.networks.access</code></li>
<li><code>compute.networks.addPeering</code></li>
<li><code>compute.networks.create</code></li>
<li><code>compute. networks. createTagBinding</code></li>
<li><code>compute.networks.delete</code></li>
<li><code>compute. networks. deleteTagBinding</code></li>
<li><code>compute.networks.get</code></li>
<li><code>compute. networks. getEffectiveFirewalls</code></li>
<li><code>compute. networks. getRegionEffectiveFirewalls</code></li>
<li><code>compute.networks.list</code></li>
<li><code>compute. networks. listEffectiveTags</code></li>
<li><code>compute. networks. listPeeringRoutes</code></li>
<li><code>compute. networks. listTagBindings</code></li>
<li><code>compute.networks.mirror</code></li>
<li><code>compute.networks.removePeering</code></li>
<li><code>compute. networks. setFirewallPolicy</code></li>
<li><code>compute. networks. setNetworkPolicy</code></li>
<li><code>compute. networks. switchToCustomMode</code></li>
<li><code>compute.networks.update</code></li>
<li><code>compute.networks.updatePeering</code></li>
<li><code>compute.networks.updatePolicy</code></li>
<li><code>compute.networks.use</code></li>
<li><code>compute.networks.useExternalIp</code></li>
</ul>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. publicDelegatedPrefixes. delete</code></p>
<p><code>compute. publicDelegatedPrefixes. get</code></p>
<p><code>compute. publicDelegatedPrefixes. list</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. publicDelegatedPrefixes. update</code></p>
<p><code>compute. publicDelegatedPrefixes. updatePolicy</code></p>
<p><code>compute.recoverableSnapshots.*</code></p>
<ul>
<li><code>compute. recoverableSnapshots. delete</code></li>
<li><code>compute. recoverableSnapshots. get</code></li>
<li><code>compute. recoverableSnapshots. getIamPolicy</code></li>
<li><code>compute. recoverableSnapshots. list</code></li>
<li><code>compute. recoverableSnapshots. recover</code></li>
<li><code>compute. recoverableSnapshots. setIamPolicy</code></li>
</ul>
<p><code>compute.regionBackendBuckets.*</code></p>
<ul>
<li><code>compute. regionBackendBuckets. create</code></li>
<li><code>compute. regionBackendBuckets. createTagBinding</code></li>
<li><code>compute. regionBackendBuckets. delete</code></li>
<li><code>compute. regionBackendBuckets. deleteTagBinding</code></li>
<li><code>compute. regionBackendBuckets. get</code></li>
<li><code>compute. regionBackendBuckets. getIamPolicy</code></li>
<li><code>compute. regionBackendBuckets. list</code></li>
<li><code>compute. regionBackendBuckets. listEffectiveTags</code></li>
<li><code>compute. regionBackendBuckets. listTagBindings</code></li>
<li><code>compute. regionBackendBuckets. setIamPolicy</code></li>
<li><code>compute. regionBackendBuckets. update</code></li>
<li><code>compute. regionBackendBuckets. use</code></li>
</ul>
<p><code>compute. regionBackendServices.*</code></p>
<ul>
<li><code>compute. regionBackendServices. create</code></li>
<li><code>compute. regionBackendServices. createTagBinding</code></li>
<li><code>compute. regionBackendServices. delete</code></li>
<li><code>compute. regionBackendServices. deleteTagBinding</code></li>
<li><code>compute. regionBackendServices. get</code></li>
<li><code>compute. regionBackendServices. getIamPolicy</code></li>
<li><code>compute. regionBackendServices. list</code></li>
<li><code>compute. regionBackendServices. listEffectiveTags</code></li>
<li><code>compute. regionBackendServices. listTagBindings</code></li>
<li><code>compute. regionBackendServices. setIamPolicy</code></li>
<li><code>compute. regionBackendServices. setSecurityPolicy</code></li>
<li><code>compute. regionBackendServices. update</code></li>
<li><code>compute. regionBackendServices. use</code></li>
</ul>
<p><code>compute. regionCompositeHealthChecks.*</code></p>
<ul>
<li><code>compute. regionCompositeHealthChecks. create</code></li>
<li><code>compute. regionCompositeHealthChecks. delete</code></li>
<li><code>compute. regionCompositeHealthChecks. get</code></li>
<li><code>compute. regionCompositeHealthChecks. list</code></li>
<li><code>compute. regionCompositeHealthChecks. update</code></li>
</ul>
<p><code>compute. regionFirewallPolicies. get</code></p>
<p><code>compute. regionFirewallPolicies. list</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionFirewallPolicies. use</code></p>
<p><code>compute. regionHealthAggregationPolicies.*</code></p>
<ul>
<li><code>compute. regionHealthAggregationPolicies. create</code></li>
<li><code>compute. regionHealthAggregationPolicies. delete</code></li>
<li><code>compute. regionHealthAggregationPolicies. get</code></li>
<li><code>compute. regionHealthAggregationPolicies. list</code></li>
<li><code>compute. regionHealthAggregationPolicies. update</code></li>
</ul>
<p><code>compute. regionHealthCheckServices.*</code></p>
<ul>
<li><code>compute. regionHealthCheckServices. create</code></li>
<li><code>compute. regionHealthCheckServices. delete</code></li>
<li><code>compute. regionHealthCheckServices. get</code></li>
<li><code>compute. regionHealthCheckServices. list</code></li>
<li><code>compute. regionHealthCheckServices. update</code></li>
<li><code>compute. regionHealthCheckServices. use</code></li>
</ul>
<p><code>compute.regionHealthChecks.*</code></p>
<ul>
<li><code>compute. regionHealthChecks. create</code></li>
<li><code>compute. regionHealthChecks. createTagBinding</code></li>
<li><code>compute. regionHealthChecks. delete</code></li>
<li><code>compute. regionHealthChecks. deleteTagBinding</code></li>
<li><code>compute.regionHealthChecks.get</code></li>
<li><code>compute. regionHealthChecks. list</code></li>
<li><code>compute. regionHealthChecks. listEffectiveTags</code></li>
<li><code>compute. regionHealthChecks. listTagBindings</code></li>
<li><code>compute. regionHealthChecks. update</code></li>
<li><code>compute.regionHealthChecks.use</code></li>
<li><code>compute. regionHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.regionHealthSources.*</code></p>
<ul>
<li><code>compute. regionHealthSources. create</code></li>
<li><code>compute. regionHealthSources. delete</code></li>
<li><code>compute. regionHealthSources. get</code></li>
<li><code>compute. regionHealthSources. list</code></li>
<li><code>compute. regionHealthSources. update</code></li>
</ul>
<p><code>compute. regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. regionNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. create</code></li>
<li><code>compute. regionNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. delete</code></li>
<li><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. get</code></li>
<li><code>compute. regionNetworkEndpointGroups. list</code></li>
<li><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. regionNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. regionNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute. regionNetworkPolicies.*</code></p>
<ul>
<li><code>compute. regionNetworkPolicies. create</code></li>
<li><code>compute. regionNetworkPolicies. delete</code></li>
<li><code>compute. regionNetworkPolicies. get</code></li>
<li><code>compute. regionNetworkPolicies. list</code></li>
<li><code>compute. regionNetworkPolicies. update</code></li>
<li><code>compute. regionNetworkPolicies. use</code></li>
</ul>
<p><code>compute. regionNotificationEndpoints.*</code></p>
<ul>
<li><code>compute. regionNotificationEndpoints. create</code></li>
<li><code>compute. regionNotificationEndpoints. delete</code></li>
<li><code>compute. regionNotificationEndpoints. get</code></li>
<li><code>compute. regionNotificationEndpoints. list</code></li>
<li><code>compute. regionNotificationEndpoints. update</code></li>
<li><code>compute. regionNotificationEndpoints. use</code></li>
</ul>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionSecurityPolicies. get</code></p>
<p><code>compute. regionSecurityPolicies. list</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSecurityPolicies. use</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute.regionSslPolicies.*</code></p>
<ul>
<li><code>compute. regionSslPolicies. create</code></li>
<li><code>compute. regionSslPolicies. createTagBinding</code></li>
<li><code>compute. regionSslPolicies. delete</code></li>
<li><code>compute. regionSslPolicies. deleteTagBinding</code></li>
<li><code>compute.regionSslPolicies.get</code></li>
<li><code>compute. regionSslPolicies. getIamPolicy</code></li>
<li><code>compute.regionSslPolicies.list</code></li>
<li><code>compute. regionSslPolicies. listAvailableFeatures</code></li>
<li><code>compute. regionSslPolicies. listEffectiveTags</code></li>
<li><code>compute. regionSslPolicies. listTagBindings</code></li>
<li><code>compute. regionSslPolicies. setIamPolicy</code></li>
<li><code>compute. regionSslPolicies. update</code></li>
<li><code>compute.regionSslPolicies.use</code></li>
</ul>
<p><code>compute. regionTargetHttpProxies.*</code></p>
<ul>
<li><code>compute. regionTargetHttpProxies. create</code></li>
<li><code>compute. regionTargetHttpProxies. createTagBinding</code></li>
<li><code>compute. regionTargetHttpProxies. delete</code></li>
<li><code>compute. regionTargetHttpProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetHttpProxies. get</code></li>
<li><code>compute. regionTargetHttpProxies. list</code></li>
<li><code>compute. regionTargetHttpProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetHttpProxies. listTagBindings</code></li>
<li><code>compute. regionTargetHttpProxies. setUrlMap</code></li>
<li><code>compute. regionTargetHttpProxies. use</code></li>
</ul>
<p><code>compute. regionTargetHttpsProxies.*</code></p>
<ul>
<li><code>compute. regionTargetHttpsProxies. create</code></li>
<li><code>compute. regionTargetHttpsProxies. createTagBinding</code></li>
<li><code>compute. regionTargetHttpsProxies. delete</code></li>
<li><code>compute. regionTargetHttpsProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetHttpsProxies. get</code></li>
<li><code>compute. regionTargetHttpsProxies. list</code></li>
<li><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetHttpsProxies. listTagBindings</code></li>
<li><code>compute. regionTargetHttpsProxies. setSslCertificates</code></li>
<li><code>compute. regionTargetHttpsProxies. setUrlMap</code></li>
<li><code>compute. regionTargetHttpsProxies. update</code></li>
<li><code>compute. regionTargetHttpsProxies. use</code></li>
</ul>
<p><code>compute. regionTargetTcpProxies.*</code></p>
<ul>
<li><code>compute. regionTargetTcpProxies. attach</code></li>
<li><code>compute. regionTargetTcpProxies. create</code></li>
<li><code>compute. regionTargetTcpProxies. createTagBinding</code></li>
<li><code>compute. regionTargetTcpProxies. delete</code></li>
<li><code>compute. regionTargetTcpProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetTcpProxies. get</code></li>
<li><code>compute. regionTargetTcpProxies. list</code></li>
<li><code>compute. regionTargetTcpProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetTcpProxies. listTagBindings</code></li>
<li><code>compute. regionTargetTcpProxies. use</code></li>
</ul>
<p><code>compute.regionUrlMaps.*</code></p>
<ul>
<li><code>compute.regionUrlMaps.create</code></li>
<li><code>compute. regionUrlMaps. createTagBinding</code></li>
<li><code>compute.regionUrlMaps.delete</code></li>
<li><code>compute. regionUrlMaps. deleteTagBinding</code></li>
<li><code>compute.regionUrlMaps.get</code></li>
<li><code>compute. regionUrlMaps. invalidateCache</code></li>
<li><code>compute.regionUrlMaps.list</code></li>
<li><code>compute. regionUrlMaps. listEffectiveTags</code></li>
<li><code>compute. regionUrlMaps. listTagBindings</code></li>
<li><code>compute.regionUrlMaps.update</code></li>
<li><code>compute.regionUrlMaps.use</code></li>
<li><code>compute.regionUrlMaps.validate</code></li>
</ul>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.reservationBlocks.get</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.*</code></p>
<ul>
<li><code>compute.reservationSlots.get</code></li>
<li><code>compute.reservationSlots.list</code></li>
<li><code>compute. reservationSlots. update</code></li>
</ul>
<p><code>compute.reservationSubBlocks.*</code></p>
<ul>
<li><code>compute. reservationSubBlocks. get</code></li>
<li><code>compute. reservationSubBlocks. list</code></li>
<li><code>compute. reservationSubBlocks. performMaintenance</code></li>
<li><code>compute. reservationSubBlocks. reportFaulty</code></li>
</ul>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute.resourcePolicies.*</code></p>
<ul>
<li><code>compute. resourcePolicies. create</code></li>
<li><code>compute. resourcePolicies. delete</code></li>
<li><code>compute.resourcePolicies.get</code></li>
<li><code>compute. resourcePolicies. getIamPolicy</code></li>
<li><code>compute.resourcePolicies.list</code></li>
<li><code>compute. resourcePolicies. setIamPolicy</code></li>
<li><code>compute. resourcePolicies. update</code></li>
<li><code>compute.resourcePolicies.use</code></li>
<li><code>compute. resourcePolicies. useReadOnly</code></li>
</ul>
<p><code>compute.routers.*</code></p>
<ul>
<li><code>compute.routers.create</code></li>
<li><code>compute. routers. createTagBinding</code></li>
<li><code>compute.routers.delete</code></li>
<li><code>compute. routers. deleteRoutePolicy</code></li>
<li><code>compute. routers. deleteTagBinding</code></li>
<li><code>compute.routers.get</code></li>
<li><code>compute.routers.getRoutePolicy</code></li>
<li><code>compute.routers.list</code></li>
<li><code>compute.routers.listBgpRoutes</code></li>
<li><code>compute. routers. listEffectiveTags</code></li>
<li><code>compute. routers. listRoutePolicies</code></li>
<li><code>compute. routers. listTagBindings</code></li>
<li><code>compute.routers.update</code></li>
<li><code>compute. routers. updateRoutePolicy</code></li>
<li><code>compute.routers.use</code></li>
</ul>
<p><code>compute.routes.*</code></p>
<ul>
<li><code>compute.routes.create</code></li>
<li><code>compute. routes. createTagBinding</code></li>
<li><code>compute.routes.delete</code></li>
<li><code>compute. routes. deleteTagBinding</code></li>
<li><code>compute.routes.get</code></li>
<li><code>compute.routes.list</code></li>
<li><code>compute. routes. listEffectiveTags</code></li>
<li><code>compute.routes.listTagBindings</code></li>
</ul>
<p><code>compute.securityPolicies.get</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute.securityPolicies.use</code></p>
<p><code>compute.serviceAttachments.*</code></p>
<ul>
<li><code>compute. serviceAttachments. create</code></li>
<li><code>compute. serviceAttachments. createTagBinding</code></li>
<li><code>compute. serviceAttachments. delete</code></li>
<li><code>compute. serviceAttachments. deleteTagBinding</code></li>
<li><code>compute.serviceAttachments.get</code></li>
<li><code>compute. serviceAttachments. getIamPolicy</code></li>
<li><code>compute. serviceAttachments. list</code></li>
<li><code>compute. serviceAttachments. listEffectiveTags</code></li>
<li><code>compute. serviceAttachments. listTagBindings</code></li>
<li><code>compute. serviceAttachments. setIamPolicy</code></li>
<li><code>compute. serviceAttachments. update</code></li>
<li><code>compute.serviceAttachments.use</code></li>
</ul>
<p><code>compute.snapshotGroups.*</code></p>
<ul>
<li><code>compute.snapshotGroups.create</code></li>
<li><code>compute.snapshotGroups.delete</code></li>
<li><code>compute.snapshotGroups.get</code></li>
<li><code>compute. snapshotGroups. getIamPolicy</code></li>
<li><code>compute.snapshotGroups.list</code></li>
<li><code>compute. snapshotGroups. setIamPolicy</code></li>
<li><code>compute. snapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute.snapshots.*</code></p>
<ul>
<li><code>compute.snapshots.create</code></li>
<li><code>compute. snapshots. createTagBinding</code></li>
<li><code>compute.snapshots.delete</code></li>
<li><code>compute. snapshots. deleteTagBinding</code></li>
<li><code>compute.snapshots.get</code></li>
<li><code>compute. snapshots. getEffectiveRecycleBinRule</code></li>
<li><code>compute.snapshots.getIamPolicy</code></li>
<li><code>compute.snapshots.list</code></li>
<li><code>compute. snapshots. listEffectiveTags</code></li>
<li><code>compute. snapshots. listTagBindings</code></li>
<li><code>compute.snapshots.setIamPolicy</code></li>
<li><code>compute.snapshots.setLabels</code></li>
<li><code>compute.snapshots.updateKmsKey</code></li>
<li><code>compute.snapshots.useReadOnly</code></li>
</ul>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute.sslPolicies.*</code></p>
<ul>
<li><code>compute.sslPolicies.create</code></li>
<li><code>compute. sslPolicies. createTagBinding</code></li>
<li><code>compute.sslPolicies.delete</code></li>
<li><code>compute. sslPolicies. deleteTagBinding</code></li>
<li><code>compute.sslPolicies.get</code></li>
<li><code>compute. sslPolicies. getIamPolicy</code></li>
<li><code>compute.sslPolicies.list</code></li>
<li><code>compute. sslPolicies. listAvailableFeatures</code></li>
<li><code>compute. sslPolicies. listEffectiveTags</code></li>
<li><code>compute. sslPolicies. listTagBindings</code></li>
<li><code>compute. sslPolicies. setIamPolicy</code></li>
<li><code>compute.sslPolicies.update</code></li>
<li><code>compute.sslPolicies.use</code></li>
</ul>
<p><code>compute.storagePools.create</code></p>
<p><code>compute.storagePools.delete</code></p>
<p><code>compute.storagePools.get</code></p>
<p><code>compute. storagePools. getIamPolicy</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute. storagePools. setIamPolicy</code></p>
<p><code>compute.storagePools.update</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.subnetworks.*</code></p>
<ul>
<li><code>compute.subnetworks.create</code></li>
<li><code>compute. subnetworks. createTagBinding</code></li>
<li><code>compute.subnetworks.delete</code></li>
<li><code>compute. subnetworks. deleteTagBinding</code></li>
<li><code>compute. subnetworks. expandIpCidrRange</code></li>
<li><code>compute.subnetworks.get</code></li>
<li><code>compute. subnetworks. getIamPolicy</code></li>
<li><code>compute.subnetworks.list</code></li>
<li><code>compute. subnetworks. listEffectiveTags</code></li>
<li><code>compute. subnetworks. listTagBindings</code></li>
<li><code>compute.subnetworks.mirror</code></li>
<li><code>compute. subnetworks. setIamPolicy</code></li>
<li><code>compute. subnetworks. setPrivateIpGoogleAccess</code></li>
<li><code>compute.subnetworks.update</code></li>
<li><code>compute.subnetworks.use</code></li>
<li><code>compute. subnetworks. useExternalIp</code></li>
<li><code>compute. subnetworks. usePeerMigration</code></li>
</ul>
<p><code>compute.targetGrpcProxies.*</code></p>
<ul>
<li><code>compute. targetGrpcProxies. create</code></li>
<li><code>compute. targetGrpcProxies. createTagBinding</code></li>
<li><code>compute. targetGrpcProxies. delete</code></li>
<li><code>compute. targetGrpcProxies. deleteTagBinding</code></li>
<li><code>compute.targetGrpcProxies.get</code></li>
<li><code>compute.targetGrpcProxies.list</code></li>
<li><code>compute. targetGrpcProxies. listEffectiveTags</code></li>
<li><code>compute. targetGrpcProxies. listTagBindings</code></li>
<li><code>compute. targetGrpcProxies. update</code></li>
<li><code>compute.targetGrpcProxies.use</code></li>
</ul>
<p><code>compute.targetHttpProxies.*</code></p>
<ul>
<li><code>compute. targetHttpProxies. create</code></li>
<li><code>compute. targetHttpProxies. createTagBinding</code></li>
<li><code>compute. targetHttpProxies. delete</code></li>
<li><code>compute. targetHttpProxies. deleteTagBinding</code></li>
<li><code>compute.targetHttpProxies.get</code></li>
<li><code>compute.targetHttpProxies.list</code></li>
<li><code>compute. targetHttpProxies. listEffectiveTags</code></li>
<li><code>compute. targetHttpProxies. listTagBindings</code></li>
<li><code>compute. targetHttpProxies. setUrlMap</code></li>
<li><code>compute. targetHttpProxies. update</code></li>
<li><code>compute.targetHttpProxies.use</code></li>
</ul>
<p><code>compute.targetHttpsProxies.*</code></p>
<ul>
<li><code>compute. targetHttpsProxies. create</code></li>
<li><code>compute. targetHttpsProxies. createTagBinding</code></li>
<li><code>compute. targetHttpsProxies. delete</code></li>
<li><code>compute. targetHttpsProxies. deleteTagBinding</code></li>
<li><code>compute.targetHttpsProxies.get</code></li>
<li><code>compute. targetHttpsProxies. list</code></li>
<li><code>compute. targetHttpsProxies. listEffectiveTags</code></li>
<li><code>compute. targetHttpsProxies. listTagBindings</code></li>
<li><code>compute. targetHttpsProxies. setCertificateMap</code></li>
<li><code>compute. targetHttpsProxies. setQuicOverride</code></li>
<li><code>compute. targetHttpsProxies. setSslCertificates</code></li>
<li><code>compute. targetHttpsProxies. setSslPolicy</code></li>
<li><code>compute. targetHttpsProxies. setUrlMap</code></li>
<li><code>compute. targetHttpsProxies. update</code></li>
<li><code>compute.targetHttpsProxies.use</code></li>
</ul>
<p><code>compute.targetInstances.*</code></p>
<ul>
<li><code>compute.targetInstances.create</code></li>
<li><code>compute. targetInstances. createTagBinding</code></li>
<li><code>compute.targetInstances.delete</code></li>
<li><code>compute. targetInstances. deleteTagBinding</code></li>
<li><code>compute.targetInstances.get</code></li>
<li><code>compute.targetInstances.list</code></li>
<li><code>compute. targetInstances. listEffectiveTags</code></li>
<li><code>compute. targetInstances. listTagBindings</code></li>
<li><code>compute. targetInstances. setSecurityPolicy</code></li>
<li><code>compute.targetInstances.use</code></li>
</ul>
<p><code>compute.targetPools.*</code></p>
<ul>
<li><code>compute. targetPools. addHealthCheck</code></li>
<li><code>compute. targetPools. addInstance</code></li>
<li><code>compute.targetPools.create</code></li>
<li><code>compute. targetPools. createTagBinding</code></li>
<li><code>compute.targetPools.delete</code></li>
<li><code>compute. targetPools. deleteTagBinding</code></li>
<li><code>compute.targetPools.get</code></li>
<li><code>compute.targetPools.list</code></li>
<li><code>compute. targetPools. listEffectiveTags</code></li>
<li><code>compute. targetPools. listTagBindings</code></li>
<li><code>compute. targetPools. removeHealthCheck</code></li>
<li><code>compute. targetPools. removeInstance</code></li>
<li><code>compute. targetPools. setSecurityPolicy</code></li>
<li><code>compute.targetPools.update</code></li>
<li><code>compute.targetPools.use</code></li>
</ul>
<p><code>compute.targetSslProxies.*</code></p>
<ul>
<li><code>compute. targetSslProxies. create</code></li>
<li><code>compute. targetSslProxies. createTagBinding</code></li>
<li><code>compute. targetSslProxies. delete</code></li>
<li><code>compute. targetSslProxies. deleteTagBinding</code></li>
<li><code>compute.targetSslProxies.get</code></li>
<li><code>compute.targetSslProxies.list</code></li>
<li><code>compute. targetSslProxies. listEffectiveTags</code></li>
<li><code>compute. targetSslProxies. listTagBindings</code></li>
<li><code>compute. targetSslProxies. setBackendService</code></li>
<li><code>compute. targetSslProxies. setCertificateMap</code></li>
<li><code>compute. targetSslProxies. setProxyHeader</code></li>
<li><code>compute. targetSslProxies. setSslCertificates</code></li>
<li><code>compute. targetSslProxies. setSslPolicy</code></li>
<li><code>compute. targetSslProxies. update</code></li>
<li><code>compute.targetSslProxies.use</code></li>
</ul>
<p><code>compute.targetTcpProxies.*</code></p>
<ul>
<li><code>compute. targetTcpProxies. attach</code></li>
<li><code>compute. targetTcpProxies. create</code></li>
<li><code>compute. targetTcpProxies. createTagBinding</code></li>
<li><code>compute. targetTcpProxies. delete</code></li>
<li><code>compute. targetTcpProxies. deleteTagBinding</code></li>
<li><code>compute.targetTcpProxies.get</code></li>
<li><code>compute.targetTcpProxies.list</code></li>
<li><code>compute. targetTcpProxies. listEffectiveTags</code></li>
<li><code>compute. targetTcpProxies. listTagBindings</code></li>
<li><code>compute. targetTcpProxies. update</code></li>
<li><code>compute.targetTcpProxies.use</code></li>
</ul>
<p><code>compute.targetVpnGateways.*</code></p>
<ul>
<li><code>compute. targetVpnGateways. create</code></li>
<li><code>compute. targetVpnGateways. createTagBinding</code></li>
<li><code>compute. targetVpnGateways. delete</code></li>
<li><code>compute. targetVpnGateways. deleteTagBinding</code></li>
<li><code>compute.targetVpnGateways.get</code></li>
<li><code>compute.targetVpnGateways.list</code></li>
<li><code>compute. targetVpnGateways. listEffectiveTags</code></li>
<li><code>compute. targetVpnGateways. listTagBindings</code></li>
<li><code>compute. targetVpnGateways. setLabels</code></li>
<li><code>compute.targetVpnGateways.use</code></li>
</ul>
<p><code>compute.urlMaps.*</code></p>
<ul>
<li><code>compute.urlMaps.create</code></li>
<li><code>compute. urlMaps. createTagBinding</code></li>
<li><code>compute.urlMaps.delete</code></li>
<li><code>compute. urlMaps. deleteTagBinding</code></li>
<li><code>compute.urlMaps.get</code></li>
<li><code>compute. urlMaps. invalidateCache</code></li>
<li><code>compute.urlMaps.list</code></li>
<li><code>compute. urlMaps. listEffectiveTags</code></li>
<li><code>compute. urlMaps. listTagBindings</code></li>
<li><code>compute.urlMaps.update</code></li>
<li><code>compute.urlMaps.use</code></li>
<li><code>compute.urlMaps.validate</code></li>
</ul>
<p><code>compute.vpnGateways.*</code></p>
<ul>
<li><code>compute.vpnGateways.create</code></li>
<li><code>compute. vpnGateways. createTagBinding</code></li>
<li><code>compute.vpnGateways.delete</code></li>
<li><code>compute. vpnGateways. deleteTagBinding</code></li>
<li><code>compute.vpnGateways.get</code></li>
<li><code>compute.vpnGateways.list</code></li>
<li><code>compute. vpnGateways. listEffectiveTags</code></li>
<li><code>compute. vpnGateways. listTagBindings</code></li>
<li><code>compute.vpnGateways.setLabels</code></li>
<li><code>compute.vpnGateways.use</code></li>
</ul>
<p><code>compute.vpnTunnels.*</code></p>
<ul>
<li><code>compute.vpnTunnels.create</code></li>
<li><code>compute. vpnTunnels. createTagBinding</code></li>
<li><code>compute.vpnTunnels.delete</code></li>
<li><code>compute. vpnTunnels. deleteTagBinding</code></li>
<li><code>compute.vpnTunnels.get</code></li>
<li><code>compute.vpnTunnels.list</code></li>
<li><code>compute. vpnTunnels. listEffectiveTags</code></li>
<li><code>compute. vpnTunnels. listTagBindings</code></li>
<li><code>compute.vpnTunnels.setLabels</code></li>
</ul>
<p><code>compute.wireGroups.*</code></p>
<ul>
<li><code>compute.wireGroups.create</code></li>
<li><code>compute.wireGroups.delete</code></li>
<li><code>compute.wireGroups.get</code></li>
<li><code>compute.wireGroups.list</code></li>
<li><code>compute.wireGroups.update</code></li>
</ul>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>dataflow.jobs.*</code></p>
<ul>
<li><code>dataflow.jobs.cancel</code></li>
<li><code>dataflow.jobs.create</code></li>
<li><code>dataflow.jobs.get</code></li>
<li><code>dataflow.jobs.list</code></li>
<li><code>dataflow.jobs.snapshot</code></li>
<li><code>dataflow.jobs.updateContents</code></li>
</ul>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.metrics.get</code></p>
<p><code>dataflow.snapshots.*</code></p>
<ul>
<li><code>dataflow.snapshots.delete</code></li>
<li><code>dataflow.snapshots.get</code></li>
<li><code>dataflow.snapshots.list</code></li>
</ul>
<p><code>dataform.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
<li><code>dataform.config.get</code></li>
<li><code>dataform.config.update</code></li>
<li><code>dataform.folders.addContents</code></li>
<li><code>dataform.folders.create</code></li>
<li><code>dataform.folders.delete</code></li>
<li><code>dataform.folders.deleteTree</code></li>
<li><code>dataform.folders.get</code></li>
<li><code>dataform.folders.getIamPolicy</code></li>
<li><code>dataform.folders.move</code></li>
<li><code>dataform.folders.queryContents</code></li>
<li><code>dataform.folders.setIamPolicy</code></li>
<li><code>dataform.folders.update</code></li>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
<li><code>dataform.operations.cancel</code></li>
<li><code>dataform.operations.delete</code></li>
<li><code>dataform.operations.get</code></li>
<li><code>dataform.operations.list</code></li>
<li><code>dataform.releaseConfigs.create</code></li>
<li><code>dataform.releaseConfigs.delete</code></li>
<li><code>dataform.releaseConfigs.get</code></li>
<li><code>dataform.releaseConfigs.list</code></li>
<li><code>dataform.releaseConfigs.update</code></li>
<li><code>dataform.repositories.commit</code></li>
<li><code>dataform. repositories. computeAccessTokenStatus</code></li>
<li><code>dataform.repositories.create</code></li>
<li><code>dataform. repositories. createTagBinding</code></li>
<li><code>dataform.repositories.delete</code></li>
<li><code>dataform. repositories. deleteTagBinding</code></li>
<li><code>dataform. repositories. fetchHistory</code></li>
<li><code>dataform. repositories. fetchRemoteBranches</code></li>
<li><code>dataform.repositories.get</code></li>
<li><code>dataform. repositories. getIamPolicy</code></li>
<li><code>dataform.repositories.list</code></li>
<li><code>dataform. repositories. listEffectiveTags</code></li>
<li><code>dataform. repositories. listTagBindings</code></li>
<li><code>dataform.repositories.move</code></li>
<li><code>dataform. repositories. queryDirectoryContents</code></li>
<li><code>dataform.repositories.readFile</code></li>
<li><code>dataform. repositories. scheduleRelease</code></li>
<li><code>dataform. repositories. scheduleWorkflow</code></li>
<li><code>dataform. repositories. setIamPolicy</code></li>
<li><code>dataform.repositories.update</code></li>
<li><code>dataform.teamFolders.create</code></li>
<li><code>dataform.teamFolders.delete</code></li>
<li><code>dataform. teamFolders. deleteTree</code></li>
<li><code>dataform.teamFolders.get</code></li>
<li><code>dataform. teamFolders. getIamPolicy</code></li>
<li><code>dataform. teamFolders. setIamPolicy</code></li>
<li><code>dataform.teamFolders.update</code></li>
<li><code>dataform. workflowConfigs. create</code></li>
<li><code>dataform. workflowConfigs. delete</code></li>
<li><code>dataform.workflowConfigs.get</code></li>
<li><code>dataform.workflowConfigs.list</code></li>
<li><code>dataform. workflowConfigs. update</code></li>
<li><code>dataform. workflowInvocations. cancel</code></li>
<li><code>dataform. workflowInvocations. create</code></li>
<li><code>dataform. workflowInvocations. delete</code></li>
<li><code>dataform. workflowInvocations. get</code></li>
<li><code>dataform. workflowInvocations. list</code></li>
<li><code>dataform. workflowInvocations. query</code></li>
<li><code>dataform.workspaces.commit</code></li>
<li><code>dataform.workspaces.create</code></li>
<li><code>dataform.workspaces.delete</code></li>
<li><code>dataform. workspaces. fetchFileDiff</code></li>
<li><code>dataform. workspaces. fetchFileGitStatuses</code></li>
<li><code>dataform. workspaces. fetchGitAheadBehind</code></li>
<li><code>dataform.workspaces.get</code></li>
<li><code>dataform. workspaces. getIamPolicy</code></li>
<li><code>dataform. workspaces. installNpmPackages</code></li>
<li><code>dataform.workspaces.list</code></li>
<li><code>dataform. workspaces. makeDirectory</code></li>
<li><code>dataform. workspaces. moveDirectory</code></li>
<li><code>dataform.workspaces.moveFile</code></li>
<li><code>dataform.workspaces.pull</code></li>
<li><code>dataform.workspaces.push</code></li>
<li><code>dataform. workspaces. queryDirectoryContents</code></li>
<li><code>dataform.workspaces.readFile</code></li>
<li><code>dataform. workspaces. removeDirectory</code></li>
<li><code>dataform.workspaces.removeFile</code></li>
<li><code>dataform.workspaces.reset</code></li>
<li><code>dataform. workspaces. searchFiles</code></li>
<li><code>dataform. workspaces. setIamPolicy</code></li>
<li><code>dataform.workspaces.writeFile</code></li>
</ul>
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
<p><code>dataplex.projects.search</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. implicitDelegation</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam.serviceAccounts.signBlob</code></p>
<p><code>iam.serviceAccounts.signJwt</code></p>
<p><code>logging.buckets.create</code></p>
<p><code>logging. buckets. createTagBinding</code></p>
<p><code>logging.buckets.delete</code></p>
<p><code>logging. buckets. deleteTagBinding</code></p>
<p><code>logging.buckets.get</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>logging.buckets.undelete</code></p>
<p><code>logging.buckets.update</code></p>
<p><code>logging.exclusions.*</code></p>
<ul>
<li><code>logging.exclusions.create</code></li>
<li><code>logging.exclusions.delete</code></li>
<li><code>logging.exclusions.get</code></li>
<li><code>logging.exclusions.list</code></li>
<li><code>logging.exclusions.update</code></li>
</ul>
<p><code>logging.links.*</code></p>
<ul>
<li><code>logging.links.create</code></li>
<li><code>logging.links.delete</code></li>
<li><code>logging.links.get</code></li>
<li><code>logging.links.list</code></li>
</ul>
<p><code>logging.locations.*</code></p>
<ul>
<li><code>logging.locations.get</code></li>
<li><code>logging.locations.list</code></li>
</ul>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>logging.logMetrics.*</code></p>
<ul>
<li><code>logging.logMetrics.create</code></li>
<li><code>logging.logMetrics.delete</code></li>
<li><code>logging.logMetrics.get</code></li>
<li><code>logging.logMetrics.list</code></li>
<li><code>logging.logMetrics.update</code></li>
</ul>
<p><code>logging.logScopes.*</code></p>
<ul>
<li><code>logging.logScopes.create</code></li>
<li><code>logging.logScopes.delete</code></li>
<li><code>logging.logScopes.get</code></li>
<li><code>logging.logScopes.list</code></li>
<li><code>logging.logScopes.update</code></li>
</ul>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.notificationRules.*</code></p>
<ul>
<li><code>logging. notificationRules. create</code></li>
<li><code>logging. notificationRules. delete</code></li>
<li><code>logging.notificationRules.get</code></li>
<li><code>logging.notificationRules.list</code></li>
<li><code>logging. notificationRules. update</code></li>
</ul>
<p><code>logging.operations.*</code></p>
<ul>
<li><code>logging.operations.cancel</code></li>
<li><code>logging.operations.get</code></li>
<li><code>logging.operations.list</code></li>
</ul>
<p><code>logging.settings.*</code></p>
<ul>
<li><code>logging.settings.get</code></li>
<li><code>logging.settings.update</code></li>
</ul>
<p><code>logging.sinks.*</code></p>
<ul>
<li><code>logging.sinks.create</code></li>
<li><code>logging.sinks.delete</code></li>
<li><code>logging.sinks.get</code></li>
<li><code>logging.sinks.list</code></li>
<li><code>logging.sinks.update</code></li>
</ul>
<p><code>logging.sqlAlerts.*</code></p>
<ul>
<li><code>logging.sqlAlerts.create</code></li>
<li><code>logging.sqlAlerts.update</code></li>
</ul>
<p><code>logging.views.create</code></p>
<p><code>logging.views.delete</code></p>
<p><code>logging.views.get</code></p>
<p><code>logging.views.getIamPolicy</code></p>
<p><code>logging.views.list</code></p>
<p><code>logging.views.update</code></p>
<p><code>monitoring. alertPolicies. create</code></p>
<p><code>monitoring. alertPolicies. delete</code></p>
<p><code>monitoring.alertPolicies.get</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring. alertPolicies. update</code></p>
<p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
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
<p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.services.get</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.get</code></p>
<p><code>monitoring.slos.list</code></p>
<p><code>monitoring.snoozes.get</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>networkconnectivity. internalRanges.*</code></p>
<ul>
<li><code>networkconnectivity. internalRanges. create</code></li>
<li><code>networkconnectivity. internalRanges. delete</code></li>
<li><code>networkconnectivity. internalRanges. get</code></li>
<li><code>networkconnectivity. internalRanges. getIamPolicy</code></li>
<li><code>networkconnectivity. internalRanges. list</code></li>
<li><code>networkconnectivity. internalRanges. setIamPolicy</code></li>
<li><code>networkconnectivity. internalRanges. update</code></li>
</ul>
<p><code>networkconnectivity. locations.*</code></p>
<ul>
<li><code>networkconnectivity. locations. get</code></li>
<li><code>networkconnectivity. locations. list</code></li>
</ul>
<p><code>networkconnectivity. operations.*</code></p>
<ul>
<li><code>networkconnectivity. operations. cancel</code></li>
<li><code>networkconnectivity. operations. delete</code></li>
<li><code>networkconnectivity. operations. get</code></li>
<li><code>networkconnectivity. operations. list</code></li>
</ul>
<p><code>networkconnectivity. policyBasedRoutes.*</code></p>
<ul>
<li><code>networkconnectivity. policyBasedRoutes. create</code></li>
<li><code>networkconnectivity. policyBasedRoutes. delete</code></li>
<li><code>networkconnectivity. policyBasedRoutes. get</code></li>
<li><code>networkconnectivity. policyBasedRoutes. getIamPolicy</code></li>
<li><code>networkconnectivity. policyBasedRoutes. list</code></li>
<li><code>networkconnectivity. policyBasedRoutes. setIamPolicy</code></li>
</ul>
<p><code>networkconnectivity. regionalEndpoints.*</code></p>
<ul>
<li><code>networkconnectivity. regionalEndpoints. create</code></li>
<li><code>networkconnectivity. regionalEndpoints. delete</code></li>
<li><code>networkconnectivity. regionalEndpoints. get</code></li>
<li><code>networkconnectivity. regionalEndpoints. list</code></li>
</ul>
<p><code>networkconnectivity. serviceClasses.*</code></p>
<ul>
<li><code>networkconnectivity. serviceClasses. create</code></li>
<li><code>networkconnectivity. serviceClasses. delete</code></li>
<li><code>networkconnectivity. serviceClasses. get</code></li>
<li><code>networkconnectivity. serviceClasses. list</code></li>
<li><code>networkconnectivity. serviceClasses. update</code></li>
<li><code>networkconnectivity. serviceClasses. use</code></li>
</ul>
<p><code>networkconnectivity. serviceConnectionMaps.*</code></p>
<ul>
<li><code>networkconnectivity. serviceConnectionMaps. create</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. delete</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. get</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. list</code></li>
<li><code>networkconnectivity. serviceConnectionMaps. update</code></li>
</ul>
<p><code>networkconnectivity. serviceConnectionPolicies.*</code></p>
<ul>
<li><code>networkconnectivity. serviceConnectionPolicies. create</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. delete</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. get</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. list</code></li>
<li><code>networkconnectivity. serviceConnectionPolicies. update</code></li>
</ul>
<p><code>networkmanagement. connectivitytests. get</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networksecurity. addressGroups.*</code></p>
<ul>
<li><code>networksecurity. addressGroups. create</code></li>
<li><code>networksecurity. addressGroups. delete</code></li>
<li><code>networksecurity. addressGroups. get</code></li>
<li><code>networksecurity. addressGroups. getIamPolicy</code></li>
<li><code>networksecurity. addressGroups. list</code></li>
<li><code>networksecurity. addressGroups. setIamPolicy</code></li>
<li><code>networksecurity. addressGroups. update</code></li>
<li><code>networksecurity. addressGroups. use</code></li>
</ul>
<p><code>networksecurity. authorizationPolicies.*</code></p>
<ul>
<li><code>networksecurity. authorizationPolicies. create</code></li>
<li><code>networksecurity. authorizationPolicies. createTagBinding</code></li>
<li><code>networksecurity. authorizationPolicies. delete</code></li>
<li><code>networksecurity. authorizationPolicies. deleteTagBinding</code></li>
<li><code>networksecurity. authorizationPolicies. get</code></li>
<li><code>networksecurity. authorizationPolicies. getIamPolicy</code></li>
<li><code>networksecurity. authorizationPolicies. list</code></li>
<li><code>networksecurity. authorizationPolicies. listEffectiveTags</code></li>
<li><code>networksecurity. authorizationPolicies. listTagBindings</code></li>
<li><code>networksecurity. authorizationPolicies. setIamPolicy</code></li>
<li><code>networksecurity. authorizationPolicies. update</code></li>
<li><code>networksecurity. authorizationPolicies. use</code></li>
</ul>
<p><code>networksecurity. authzPolicies.*</code></p>
<ul>
<li><code>networksecurity. authzPolicies. create</code></li>
<li><code>networksecurity. authzPolicies. delete</code></li>
<li><code>networksecurity. authzPolicies. get</code></li>
<li><code>networksecurity. authzPolicies. getIamPolicy</code></li>
<li><code>networksecurity. authzPolicies. list</code></li>
<li><code>networksecurity. authzPolicies. setIamPolicy</code></li>
<li><code>networksecurity. authzPolicies. update</code></li>
</ul>
<p><code>networksecurity. backendAuthenticationConfigs.*</code></p>
<ul>
<li><code>networksecurity. backendAuthenticationConfigs. create</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. delete</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. get</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. list</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. update</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. use</code></li>
</ul>
<p><code>networksecurity. clientTlsPolicies.*</code></p>
<ul>
<li><code>networksecurity. clientTlsPolicies. create</code></li>
<li><code>networksecurity. clientTlsPolicies. createTagBinding</code></li>
<li><code>networksecurity. clientTlsPolicies. delete</code></li>
<li><code>networksecurity. clientTlsPolicies. deleteTagBinding</code></li>
<li><code>networksecurity. clientTlsPolicies. get</code></li>
<li><code>networksecurity. clientTlsPolicies. getIamPolicy</code></li>
<li><code>networksecurity. clientTlsPolicies. list</code></li>
<li><code>networksecurity. clientTlsPolicies. listEffectiveTags</code></li>
<li><code>networksecurity. clientTlsPolicies. listTagBindings</code></li>
<li><code>networksecurity. clientTlsPolicies. setIamPolicy</code></li>
<li><code>networksecurity. clientTlsPolicies. update</code></li>
<li><code>networksecurity. clientTlsPolicies. use</code></li>
</ul>
<p><code>networksecurity. firewallEndpointAssociations.*</code></p>
<ul>
<li><code>networksecurity. firewallEndpointAssociations. create</code></li>
<li><code>networksecurity. firewallEndpointAssociations. delete</code></li>
<li><code>networksecurity. firewallEndpointAssociations. get</code></li>
<li><code>networksecurity. firewallEndpointAssociations. list</code></li>
<li><code>networksecurity. firewallEndpointAssociations. update</code></li>
</ul>
<p><code>networksecurity. firewallEndpoints.*</code></p>
<ul>
<li><code>networksecurity. firewallEndpoints. create</code></li>
<li><code>networksecurity. firewallEndpoints. createVerdictChangeRequest</code></li>
<li><code>networksecurity. firewallEndpoints. delete</code></li>
<li><code>networksecurity. firewallEndpoints. get</code></li>
<li><code>networksecurity. firewallEndpoints. getVerdictChangeRequest</code></li>
<li><code>networksecurity. firewallEndpoints. getWildfireReport</code></li>
<li><code>networksecurity. firewallEndpoints. getWildfireSample</code></li>
<li><code>networksecurity. firewallEndpoints. list</code></li>
<li><code>networksecurity. firewallEndpoints. listVerdictChangeRequests</code></li>
<li><code>networksecurity. firewallEndpoints. submitVerdictChangeRequest</code></li>
<li><code>networksecurity. firewallEndpoints. update</code></li>
<li><code>networksecurity. firewallEndpoints. use</code></li>
<li><code>networksecurity. firewallEndpoints. useWildfire</code></li>
</ul>
<p><code>networksecurity. gatewaySecurityPolicies.*</code></p>
<ul>
<li><code>networksecurity. gatewaySecurityPolicies. create</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. delete</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. get</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. list</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. update</code></li>
<li><code>networksecurity. gatewaySecurityPolicies. use</code></li>
</ul>
<p><code>networksecurity. gatewaySecurityPolicyRules.*</code></p>
<ul>
<li><code>networksecurity. gatewaySecurityPolicyRules. create</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. delete</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. get</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. list</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. update</code></li>
<li><code>networksecurity. gatewaySecurityPolicyRules. use</code></li>
</ul>
<p><code>networksecurity.locations.*</code></p>
<ul>
<li><code>networksecurity.locations.get</code></li>
<li><code>networksecurity.locations.list</code></li>
</ul>
<p><code>networksecurity.operations.*</code></p>
<ul>
<li><code>networksecurity. operations. cancel</code></li>
<li><code>networksecurity. operations. delete</code></li>
<li><code>networksecurity.operations.get</code></li>
<li><code>networksecurity. operations. list</code></li>
</ul>
<p><code>networksecurity. sacAttachments.*</code></p>
<ul>
<li><code>networksecurity. sacAttachments. create</code></li>
<li><code>networksecurity. sacAttachments. delete</code></li>
<li><code>networksecurity. sacAttachments. get</code></li>
<li><code>networksecurity. sacAttachments. list</code></li>
</ul>
<p><code>networksecurity.sacRealms.*</code></p>
<ul>
<li><code>networksecurity. sacRealms. create</code></li>
<li><code>networksecurity. sacRealms. delete</code></li>
<li><code>networksecurity.sacRealms.get</code></li>
<li><code>networksecurity.sacRealms.list</code></li>
</ul>
<p><code>networksecurity. securityProfileGroups.*</code></p>
<ul>
<li><code>networksecurity. securityProfileGroups. create</code></li>
<li><code>networksecurity. securityProfileGroups. delete</code></li>
<li><code>networksecurity. securityProfileGroups. get</code></li>
<li><code>networksecurity. securityProfileGroups. list</code></li>
<li><code>networksecurity. securityProfileGroups. update</code></li>
<li><code>networksecurity. securityProfileGroups. use</code></li>
</ul>
<p><code>networksecurity. securityProfiles.*</code></p>
<ul>
<li><code>networksecurity. securityProfiles. create</code></li>
<li><code>networksecurity. securityProfiles. delete</code></li>
<li><code>networksecurity. securityProfiles. get</code></li>
<li><code>networksecurity. securityProfiles. list</code></li>
<li><code>networksecurity. securityProfiles. update</code></li>
<li><code>networksecurity. securityProfiles. use</code></li>
</ul>
<p><code>networksecurity. serverTlsPolicies.*</code></p>
<ul>
<li><code>networksecurity. serverTlsPolicies. create</code></li>
<li><code>networksecurity. serverTlsPolicies. createTagBinding</code></li>
<li><code>networksecurity. serverTlsPolicies. delete</code></li>
<li><code>networksecurity. serverTlsPolicies. deleteTagBinding</code></li>
<li><code>networksecurity. serverTlsPolicies. get</code></li>
<li><code>networksecurity. serverTlsPolicies. getIamPolicy</code></li>
<li><code>networksecurity. serverTlsPolicies. list</code></li>
<li><code>networksecurity. serverTlsPolicies. listEffectiveTags</code></li>
<li><code>networksecurity. serverTlsPolicies. listTagBindings</code></li>
<li><code>networksecurity. serverTlsPolicies. setIamPolicy</code></li>
<li><code>networksecurity. serverTlsPolicies. update</code></li>
<li><code>networksecurity. serverTlsPolicies. use</code></li>
</ul>
<p><code>networksecurity. tlsInspectionPolicies.*</code></p>
<ul>
<li><code>networksecurity. tlsInspectionPolicies. create</code></li>
<li><code>networksecurity. tlsInspectionPolicies. delete</code></li>
<li><code>networksecurity. tlsInspectionPolicies. get</code></li>
<li><code>networksecurity. tlsInspectionPolicies. list</code></li>
<li><code>networksecurity. tlsInspectionPolicies. update</code></li>
<li><code>networksecurity. tlsInspectionPolicies. use</code></li>
</ul>
<p><code>networksecurity.urlLists.*</code></p>
<ul>
<li><code>networksecurity. urlLists. create</code></li>
<li><code>networksecurity. urlLists. delete</code></li>
<li><code>networksecurity.urlLists.get</code></li>
<li><code>networksecurity.urlLists.list</code></li>
<li><code>networksecurity. urlLists. update</code></li>
<li><code>networksecurity.urlLists.use</code></li>
</ul>
<p><code>networkservices.*</code></p>
<ul>
<li><code>networkservices. agentGateways. create</code></li>
<li><code>networkservices. agentGateways. delete</code></li>
<li><code>networkservices. agentGateways. get</code></li>
<li><code>networkservices. agentGateways. list</code></li>
<li><code>networkservices. agentGateways. update</code></li>
<li><code>networkservices. agentGateways. use</code></li>
<li><code>networkservices. authzExtensions. create</code></li>
<li><code>networkservices. authzExtensions. delete</code></li>
<li><code>networkservices. authzExtensions. get</code></li>
<li><code>networkservices. authzExtensions. list</code></li>
<li><code>networkservices. authzExtensions. update</code></li>
<li><code>networkservices. authzExtensions. use</code></li>
<li><code>networkservices. endpointConfigSelectors. createTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. deleteTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. listEffectiveTags</code></li>
<li><code>networkservices. endpointConfigSelectors. listTagBindings</code></li>
<li><code>networkservices. endpointPolicies. create</code></li>
<li><code>networkservices. endpointPolicies. delete</code></li>
<li><code>networkservices. endpointPolicies. get</code></li>
<li><code>networkservices. endpointPolicies. list</code></li>
<li><code>networkservices. endpointPolicies. update</code></li>
<li><code>networkservices. gateways. create</code></li>
<li><code>networkservices. gateways. createTagBinding</code></li>
<li><code>networkservices. gateways. delete</code></li>
<li><code>networkservices. gateways. deleteTagBinding</code></li>
<li><code>networkservices.gateways.get</code></li>
<li><code>networkservices.gateways.list</code></li>
<li><code>networkservices. gateways. listEffectiveTags</code></li>
<li><code>networkservices. gateways. listTagBindings</code></li>
<li><code>networkservices. gateways. update</code></li>
<li><code>networkservices.gateways.use</code></li>
<li><code>networkservices. googleTagGatewayPolicies. create</code></li>
<li><code>networkservices. googleTagGatewayPolicies. delete</code></li>
<li><code>networkservices. googleTagGatewayPolicies. get</code></li>
<li><code>networkservices. googleTagGatewayPolicies. list</code></li>
<li><code>networkservices. googleTagGatewayPolicies. update</code></li>
<li><code>networkservices. grpcRoutes. create</code></li>
<li><code>networkservices. grpcRoutes. delete</code></li>
<li><code>networkservices.grpcRoutes.get</code></li>
<li><code>networkservices. grpcRoutes. list</code></li>
<li><code>networkservices. grpcRoutes. update</code></li>
<li><code>networkservices. httpFilters. create</code></li>
<li><code>networkservices. httpFilters. createTagBinding</code></li>
<li><code>networkservices. httpFilters. delete</code></li>
<li><code>networkservices. httpFilters. deleteTagBinding</code></li>
<li><code>networkservices. httpFilters. get</code></li>
<li><code>networkservices. httpFilters. list</code></li>
<li><code>networkservices. httpFilters. listEffectiveTags</code></li>
<li><code>networkservices. httpFilters. listTagBindings</code></li>
<li><code>networkservices. httpFilters. update</code></li>
<li><code>networkservices. httpRoutes. create</code></li>
<li><code>networkservices. httpRoutes. delete</code></li>
<li><code>networkservices.httpRoutes.get</code></li>
<li><code>networkservices. httpRoutes. list</code></li>
<li><code>networkservices. httpRoutes. update</code></li>
<li><code>networkservices. httpfilters. create</code></li>
<li><code>networkservices. httpfilters. delete</code></li>
<li><code>networkservices. httpfilters. get</code></li>
<li><code>networkservices. httpfilters. getIamPolicy</code></li>
<li><code>networkservices. httpfilters. list</code></li>
<li><code>networkservices. httpfilters. setIamPolicy</code></li>
<li><code>networkservices. httpfilters. update</code></li>
<li><code>networkservices. httpfilters. use</code></li>
<li><code>networkservices. lbEdgeExtensions. create</code></li>
<li><code>networkservices. lbEdgeExtensions. delete</code></li>
<li><code>networkservices. lbEdgeExtensions. get</code></li>
<li><code>networkservices. lbEdgeExtensions. list</code></li>
<li><code>networkservices. lbEdgeExtensions. update</code></li>
<li><code>networkservices. lbRouteExtensions. create</code></li>
<li><code>networkservices. lbRouteExtensions. delete</code></li>
<li><code>networkservices. lbRouteExtensions. get</code></li>
<li><code>networkservices. lbRouteExtensions. list</code></li>
<li><code>networkservices. lbRouteExtensions. update</code></li>
<li><code>networkservices. lbTcpExtensions. createForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. deleteForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. getForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. listForNetwork</code></li>
<li><code>networkservices. lbTcpExtensions. updateForNetwork</code></li>
<li><code>networkservices. lbTrafficExtensions. create</code></li>
<li><code>networkservices. lbTrafficExtensions. delete</code></li>
<li><code>networkservices. lbTrafficExtensions. get</code></li>
<li><code>networkservices. lbTrafficExtensions. list</code></li>
<li><code>networkservices. lbTrafficExtensions. update</code></li>
<li><code>networkservices.locations.get</code></li>
<li><code>networkservices.locations.list</code></li>
<li><code>networkservices.meshes.create</code></li>
<li><code>networkservices. meshes. createTagBinding</code></li>
<li><code>networkservices.meshes.delete</code></li>
<li><code>networkservices. meshes. deleteTagBinding</code></li>
<li><code>networkservices.meshes.get</code></li>
<li><code>networkservices.meshes.list</code></li>
<li><code>networkservices. meshes. listEffectiveTags</code></li>
<li><code>networkservices. meshes. listTagBindings</code></li>
<li><code>networkservices.meshes.update</code></li>
<li><code>networkservices.meshes.use</code></li>
<li><code>networkservices. operations. cancel</code></li>
<li><code>networkservices. operations. delete</code></li>
<li><code>networkservices.operations.get</code></li>
<li><code>networkservices. operations. list</code></li>
<li><code>networkservices. route_views. get</code></li>
<li><code>networkservices. route_views. list</code></li>
<li><code>networkservices. serviceBindings. create</code></li>
<li><code>networkservices. serviceBindings. delete</code></li>
<li><code>networkservices. serviceBindings. get</code></li>
<li><code>networkservices. serviceBindings. list</code></li>
<li><code>networkservices. serviceBindings. update</code></li>
<li><code>networkservices. serviceLbPolicies. create</code></li>
<li><code>networkservices. serviceLbPolicies. delete</code></li>
<li><code>networkservices. serviceLbPolicies. get</code></li>
<li><code>networkservices. serviceLbPolicies. list</code></li>
<li><code>networkservices. serviceLbPolicies. update</code></li>
<li><code>networkservices. swpSecurityExtensions. create</code></li>
<li><code>networkservices. swpSecurityExtensions. delete</code></li>
<li><code>networkservices. swpSecurityExtensions. get</code></li>
<li><code>networkservices. swpSecurityExtensions. list</code></li>
<li><code>networkservices. swpSecurityExtensions. update</code></li>
<li><code>networkservices. tcpRoutes. create</code></li>
<li><code>networkservices. tcpRoutes. delete</code></li>
<li><code>networkservices.tcpRoutes.get</code></li>
<li><code>networkservices.tcpRoutes.list</code></li>
<li><code>networkservices. tcpRoutes. update</code></li>
<li><code>networkservices. tlsRoutes. create</code></li>
<li><code>networkservices. tlsRoutes. delete</code></li>
<li><code>networkservices.tlsRoutes.get</code></li>
<li><code>networkservices.tlsRoutes.list</code></li>
<li><code>networkservices. tlsRoutes. update</code></li>
<li><code>networkservices. wasmPlugins. create</code></li>
<li><code>networkservices. wasmPlugins. delete</code></li>
<li><code>networkservices. wasmPlugins. get</code></li>
<li><code>networkservices. wasmPlugins. list</code></li>
<li><code>networkservices. wasmPlugins. update</code></li>
<li><code>networkservices. wasmPlugins. use</code></li>
</ul>
<p><code>observability.scopes.get</code></p>
<p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>pubsub.*</code></p>
<ul>
<li><code>pubsub. messageTransforms. validate</code></li>
<li><code>pubsub.schemas.attach</code></li>
<li><code>pubsub.schemas.commit</code></li>
<li><code>pubsub.schemas.create</code></li>
<li><code>pubsub.schemas.delete</code></li>
<li><code>pubsub.schemas.get</code></li>
<li><code>pubsub.schemas.getIamPolicy</code></li>
<li><code>pubsub.schemas.list</code></li>
<li><code>pubsub.schemas.listRevisions</code></li>
<li><code>pubsub.schemas.rollback</code></li>
<li><code>pubsub.schemas.setIamPolicy</code></li>
<li><code>pubsub.schemas.validate</code></li>
<li><code>pubsub.snapshots.create</code></li>
<li><code>pubsub. snapshots. createTagBinding</code></li>
<li><code>pubsub.snapshots.delete</code></li>
<li><code>pubsub. snapshots. deleteTagBinding</code></li>
<li><code>pubsub.snapshots.get</code></li>
<li><code>pubsub.snapshots.getIamPolicy</code></li>
<li><code>pubsub.snapshots.list</code></li>
<li><code>pubsub. snapshots. listEffectiveTags</code></li>
<li><code>pubsub. snapshots. listTagBindings</code></li>
<li><code>pubsub.snapshots.seek</code></li>
<li><code>pubsub.snapshots.setIamPolicy</code></li>
<li><code>pubsub.snapshots.update</code></li>
<li><code>pubsub.subscriptions.consume</code></li>
<li><code>pubsub.subscriptions.create</code></li>
<li><code>pubsub. subscriptions. createTagBinding</code></li>
<li><code>pubsub.subscriptions.delete</code></li>
<li><code>pubsub. subscriptions. deleteTagBinding</code></li>
<li><code>pubsub.subscriptions.get</code></li>
<li><code>pubsub. subscriptions. getIamPolicy</code></li>
<li><code>pubsub.subscriptions.list</code></li>
<li><code>pubsub. subscriptions. listEffectiveTags</code></li>
<li><code>pubsub. subscriptions. listTagBindings</code></li>
<li><code>pubsub. subscriptions. setIamPolicy</code></li>
<li><code>pubsub.subscriptions.update</code></li>
<li><code>pubsub. topics. attachSubscription</code></li>
<li><code>pubsub.topics.create</code></li>
<li><code>pubsub.topics.createTagBinding</code></li>
<li><code>pubsub.topics.delete</code></li>
<li><code>pubsub.topics.deleteTagBinding</code></li>
<li><code>pubsub. topics. detachSubscription</code></li>
<li><code>pubsub.topics.get</code></li>
<li><code>pubsub.topics.getIamPolicy</code></li>
<li><code>pubsub.topics.list</code></li>
<li><code>pubsub. topics. listEffectiveTags</code></li>
<li><code>pubsub.topics.listTagBindings</code></li>
<li><code>pubsub.topics.publish</code></li>
<li><code>pubsub.topics.setIamPolicy</code></li>
<li><code>pubsub.topics.update</code></li>
<li><code>pubsub.topics.updateTag</code></li>
</ul>
<p><code>recommender. dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code>recommender. dataflowDiagnosticsInsights. get</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. list</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. update</code></li>
</ul>
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
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. namespaces. delete</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicedirectory. services. delete</code></p>
<p><code>servicenetworking. operations. get</code></p>
<p><code>servicenetworking. services. addPeering</code></p>
<p><code>servicenetworking. services. createPeeredDnsDomain</code></p>
<p><code>servicenetworking. services. deleteConnection</code></p>
<p><code>servicenetworking. services. deletePeeredDnsDomain</code></p>
<p><code>servicenetworking. services. disableVpcServiceControls</code></p>
<p><code>servicenetworking. services. enableVpcServiceControls</code></p>
<p><code>servicenetworking.services.get</code></p>
<p><code>servicenetworking. services. getVpcServiceControls</code></p>
<p><code>servicenetworking. services. listPeeredDnsDomains</code></p>
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
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p>
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

## Dataflow permissions

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
<td><code>dataflow.jobs.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataflow.jobs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataflow.jobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataflow.jobs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataflow.jobs.snapshot</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataflow.jobs.updateContents</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataflow.messages.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataflow.metrics.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataflow.shuffle.read</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataflow.shuffle.write</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataflow.snapshots.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataflow.snapshots.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataflow.snapshots.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataflow. streamingWorkItems. ImportState</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataflow. streamingWorkItems. commitWork</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataflow. streamingWorkItems. getData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataflow. streamingWorkItems. getWork</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataflow. streamingWorkItems. getWorkerMetadata</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataflow.workItems.lease</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dataflow.workItems.sendMessage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dataflow.workItems.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
