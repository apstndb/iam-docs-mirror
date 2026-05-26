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
<td><h4 id="dataflow.admin" class="role-title add-link" data-text="Dataflow Admin" tabindex="-1">Dataflow Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p>Minimal role for creating and managing dataflow jobs.</p></td>
<td><p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.create</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.get</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.list</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.snapshot</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.updateContents</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.metrics.get</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.get</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.viewer" class="role-title add-link" data-text="Dataflow Viewer" tabindex="-1">Dataflow Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p>Provides read-only access to all Dataflow-related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">dataflow.jobs.get</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.list</code></p>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.metrics.get</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.get</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.list</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.developer" class="role-title add-link" data-text="Dataflow Developer" tabindex="-1">Dataflow Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p>Provides the permissions necessary to execute and manipulate Dataflow jobs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.create</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.get</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.list</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.snapshot</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.updateContents</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.metrics.get</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.get</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.worker" class="role-title add-link" data-text="Dataflow Worker" tabindex="-1">Dataflow Worker</h4>
<p>( <code dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p>Provides the permissions necessary for a Compute Engine service account to execute work units for a Dataflow pipeline.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">autoscaling.  sites.  readRecommendations</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.writeState</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setDiskAutoDelete</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.get</code></p>
<p><code dir="ltr" translate="no">dataflow.shuffle.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.shuffle.read</code></li>
<li><code dir="ltr" translate="no">dataflow.shuffle.write</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.streamingWorkItems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  ImportState</code></li>
<li><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  commitWork</code></li>
<li><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  getData</code></li>
<li><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  getWork</code></li>
<li><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  getWorkerMetadata</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.workItems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.workItems.lease</code></li>
<li><code dir="ltr" translate="no">dataflow.workItems.sendMessage</code></li>
<li><code dir="ltr" translate="no">dataflow.workItems.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
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
<td><h4 id="dataflow.serviceAgent" class="role-title add-link" data-text="Cloud Dataflow Service Agent" tabindex="-1">Cloud Dataflow Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</p>
<p>Gives Cloud Dataflow service account access to managed resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">bigquery.bireservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.bireservations.get</code></li>
<li><code dir="ltr" translate="no">bigquery.bireservations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.capacityCommitments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  get</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.  capacityCommitments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.config.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.config.get</code></li>
<li><code dir="ltr" translate="no">bigquery.config.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.connections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.connections.create</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.delegate</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.get</code></li>
<li><code dir="ltr" translate="no">bigquery.  connections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  connections.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.update</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.updateTag</code></li>
<li><code dir="ltr" translate="no">bigquery.connections.use</code></li>
</ul>
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
<p><code dir="ltr" translate="no">bigquery.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.jobs.create</code></li>
<li><code dir="ltr" translate="no">bigquery.  jobs.  createGlobalQuery</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.get</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.list</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.listAll</code></li>
<li><code dir="ltr" translate="no">bigquery.  jobs.  listExecutionMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.jobs.update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">bigquery.objectRefs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.objectRefs.read</code></li>
<li><code dir="ltr" translate="no">bigquery.objectRefs.write</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.readsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.readsessions.create</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationAssignments.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.reservationGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.  reservationGroups.  create</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationGroups.  delete</code></li>
<li><code dir="ltr" translate="no">bigquery.reservationGroups.get</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.reservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.reservations.create</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.get</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservations.  listFailoverDatasets</code></li>
<li><code dir="ltr" translate="no">bigquery.  reservations.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.update</code></li>
<li><code dir="ltr" translate="no">bigquery.reservations.use</code></li>
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
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  overrideTimeTravelRestrictions</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.savedqueries.create</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.get</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.list</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">bigquery.transfers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.transfers.get</code></li>
<li><code dir="ltr" translate="no">bigquery.transfers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">clouddebugger.breakpoints.list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.  breakpoints.  listActive</code></p>
<p><code dir="ltr" translate="no">clouddebugger.  breakpoints.  update</code></p>
<p><code dir="ltr" translate="no">clouddebugger.debuggees.create</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.addresses.create</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.addresses.delete</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.addresses.get</code></li>
<li><code dir="ltr" translate="no">compute.addresses.list</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.addresses.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.addresses.use</code></li>
<li><code dir="ltr" translate="no">compute.addresses.useInternal</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.autoscalers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.autoscalers.create</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.delete</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.get</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.list</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.backendBuckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  addSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.create</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.delete</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  deleteSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.get</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.list</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  backendBuckets.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.update</code></li>
<li><code dir="ltr" translate="no">compute.backendBuckets.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.backendServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  backendServices.  addSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.create</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.delete</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  deleteSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.get</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.list</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.update</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  crossSiteNetworks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  crossSiteNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></li>
<li><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></li>
<li><code dir="ltr" translate="no">compute.  crossSiteNetworks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.diskSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskSettings.get</code></li>
<li><code dir="ltr" translate="no">compute.diskSettings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  disks.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.create</code></li>
<li><code dir="ltr" translate="no">compute.disks.createSnapshot</code></li>
<li><code dir="ltr" translate="no">compute.disks.createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.delete</code></li>
<li><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.get</code></li>
<li><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.list</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.disks.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.resize</code></li>
<li><code dir="ltr" translate="no">compute.disks.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  startAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopGroupAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.disks.update</code></li>
<li><code dir="ltr" translate="no">compute.disks.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.disks.use</code></li>
<li><code dir="ltr" translate="no">compute.disks.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.externalVpnGateways.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  create</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  externalVpnGateways.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.firewallPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.forwardingRules.create</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.delete</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.get</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.list</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscSetLabels</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscUpdate</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  setTarget</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.update</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalAddresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.globalAddresses.create</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  createInternal</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  deleteInternal</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.get</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.list</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalAddresses.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.globalAddresses.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscCreate</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscDelete</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscSetLabels</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscUpdate</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  setTarget</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.healthChecks.create</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.update</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.images.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.images.create</code></li>
<li><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.delete</code></li>
<li><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.deprecate</code></li>
<li><code dir="ltr" translate="no">compute.images.get</code></li>
<li><code dir="ltr" translate="no">compute.images.getFromFamily</code></li>
<li><code dir="ltr" translate="no">compute.images.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.list</code></li>
<li><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.images.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.images.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.images.update</code></li>
<li><code dir="ltr" translate="no">compute.images.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.update</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instances.  addAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.attachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.create</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.detachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.get</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></li>
<li><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedInstanceIdentity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedVmIdentity</code></li>
<li><code dir="ltr" translate="no">compute.instances.list</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instances.osAdminLogin</code></li>
<li><code dir="ltr" translate="no">compute.instances.osLogin</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.reset</code></li>
<li><code dir="ltr" translate="no">compute.instances.resume</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  sendDiagnosticInterrupt</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDiskAutoDelete</code></li>
<li><code dir="ltr" translate="no">compute.instances.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineResources</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineType</code></li>
<li><code dir="ltr" translate="no">compute.instances.setMetadata</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMinCpuPlatform</code></li>
<li><code dir="ltr" translate="no">compute.instances.setName</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setScheduling</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedInstanceIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedVmIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  simulateMaintenanceEvent</code></li>
<li><code dir="ltr" translate="no">compute.instances.start</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  startWithEncryptionKey</code></li>
<li><code dir="ltr" translate="no">compute.instances.stop</code></li>
<li><code dir="ltr" translate="no">compute.instances.suspend</code></li>
<li><code dir="ltr" translate="no">compute.instances.update</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateSecurity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedInstanceConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedVmConfig</code></li>
<li><code dir="ltr" translate="no">compute.instances.use</code></li>
<li><code dir="ltr" translate="no">compute.instances.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  export</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  patch</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  update</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectAttachments.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.interconnectGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.interconnectGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectGroups.  patch</code></li>
</ul>
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
<p><code dir="ltr" translate="no">compute.interconnects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.interconnects.create</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.delete</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  getMacsecConfig</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.list</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  interconnects.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.update</code></li>
<li><code dir="ltr" translate="no">compute.interconnects.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.licenseCodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.licenseCodes.get</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.licenseCodes.list</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.licenses.create</code></p>
<p><code dir="ltr" translate="no">compute.licenses.delete</code></p>
<p><code dir="ltr" translate="no">compute.licenses.get</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenses.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.update</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineImages.create</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.machineImages.delete</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.machineImages.get</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.machineImages.list</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  machineImages.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMig.create</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.delete</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMigMembers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMigMembers.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMigMembers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  create</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.networkAttachments.get</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networkAttachments.  update</code></li>
<li><code dir="ltr" translate="no">compute.networkAttachments.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networks.access</code></li>
<li><code dir="ltr" translate="no">compute.networks.addPeering</code></li>
<li><code dir="ltr" translate="no">compute.networks.create</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.networks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.networks.get</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  getRegionEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.networks.list</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.networks.mirror</code></li>
<li><code dir="ltr" translate="no">compute.networks.removePeering</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  setFirewallPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  setNetworkPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  networks.  switchToCustomMode</code></li>
<li><code dir="ltr" translate="no">compute.networks.update</code></li>
<li><code dir="ltr" translate="no">compute.networks.updatePeering</code></li>
<li><code dir="ltr" translate="no">compute.networks.updatePolicy</code></li>
<li><code dir="ltr" translate="no">compute.networks.use</code></li>
<li><code dir="ltr" translate="no">compute.networks.useExternalIp</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  update</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.regionBackendBuckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendBuckets.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.regionHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionHealthSources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthSources.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslPolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.regionSslPolicies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  attach</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.create</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  invalidateCache</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.update</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.use</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservationBlocks.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationSubBlocks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  get</code></li>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  performMaintenance</code></li>
<li><code dir="ltr" translate="no">compute.  reservationSubBlocks.  reportFaulty</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.use</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.routers.create</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routers.delete</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  deleteRoutePolicy</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routers.get</code></li>
<li><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></li>
<li><code dir="ltr" translate="no">compute.routers.list</code></li>
<li><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.routers.update</code></li>
<li><code dir="ltr" translate="no">compute.  routers.  updateRoutePolicy</code></li>
<li><code dir="ltr" translate="no">compute.routers.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.routes.create</code></li>
<li><code dir="ltr" translate="no">compute.  routes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routes.delete</code></li>
<li><code dir="ltr" translate="no">compute.  routes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.routes.get</code></li>
<li><code dir="ltr" translate="no">compute.routes.list</code></li>
<li><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.routes.listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.securityPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  create</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.serviceAttachments.get</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  serviceAttachments.  update</code></li>
<li><code dir="ltr" translate="no">compute.serviceAttachments.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.snapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshotGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshots.create</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.get</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.sslPolicies.create</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.delete</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.update</code></li>
<li><code dir="ltr" translate="no">compute.sslPolicies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.storagePools.create</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.delete</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.get</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.update</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.subnetworks.create</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  expandIpCidrRange</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.get</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.list</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.mirror</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  setPrivateIpGoogleAccess</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.update</code></li>
<li><code dir="ltr" translate="no">compute.subnetworks.use</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></li>
<li><code dir="ltr" translate="no">compute.  subnetworks.  usePeerMigration</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetGrpcProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetGrpcProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setCertificateMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setQuicOverride</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpsProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetInstances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.targetInstances.create</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.get</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetInstances.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.targetInstances.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetPools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetPools.  addHealthCheck</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  addInstance</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.create</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.get</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  removeHealthCheck</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  removeInstance</code></li>
<li><code dir="ltr" translate="no">compute.  targetPools.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.update</code></li>
<li><code dir="ltr" translate="no">compute.targetPools.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetSslProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetSslProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetSslProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setBackendService</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setCertificateMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setProxyHeader</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  setSslPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  targetSslProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetSslProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  attach</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></li>
<li><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetVpnGateways.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.targetVpnGateways.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.urlMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.urlMaps.create</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.delete</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.get</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  invalidateCache</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.list</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.update</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.use</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.vpnGateways.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.vpnGateways.create</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.delete</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.get</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.list</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.vpnGateways.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.vpnTunnels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.vpnTunnels.create</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.delete</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.get</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.list</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.vpnTunnels.setLabels</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.wireGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.wireGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.wireGroups.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.create</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.get</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.list</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.snapshot</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.updateContents</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.metrics.get</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.get</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
<li><code dir="ltr" translate="no">dataform.config.get</code></li>
<li><code dir="ltr" translate="no">dataform.config.update</code></li>
<li><code dir="ltr" translate="no">dataform.folders.addContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.create</code></li>
<li><code dir="ltr" translate="no">dataform.folders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.folders.deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.folders.get</code></li>
<li><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.move</code></li>
<li><code dir="ltr" translate="no">dataform.folders.queryContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.update</code></li>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
<li><code dir="ltr" translate="no">dataform.operations.cancel</code></li>
<li><code dir="ltr" translate="no">dataform.operations.delete</code></li>
<li><code dir="ltr" translate="no">dataform.operations.get</code></li>
<li><code dir="ltr" translate="no">dataform.operations.list</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.create</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.delete</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.get</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.update</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.commit</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.create</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.get</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.list</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.move</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  scheduleRelease</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  scheduleWorkflow</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.update</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.create</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.get</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.update</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.workflowConfigs.get</code></li>
<li><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  update</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  query</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.commit</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.create</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.get</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.pull</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.push</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.reset</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></li>
</ul>
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
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  implicitDelegation</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signJwt</code></p>
<p><code dir="ltr" translate="no">logging.buckets.create</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.buckets.delete</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">logging.buckets.undelete</code></p>
<p><code dir="ltr" translate="no">logging.buckets.update</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.exclusions.create</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.delete</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.get</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.list</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.links.create</code></li>
<li><code dir="ltr" translate="no">logging.links.delete</code></li>
<li><code dir="ltr" translate="no">logging.links.get</code></li>
<li><code dir="ltr" translate="no">logging.links.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.locations.get</code></li>
<li><code dir="ltr" translate="no">logging.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.logMetrics.create</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.delete</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.get</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.list</code></li>
<li><code dir="ltr" translate="no">logging.logMetrics.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.logScopes.create</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.delete</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.get</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.list</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.  notificationRules.  create</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  delete</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.get</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.list</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.operations.cancel</code></li>
<li><code dir="ltr" translate="no">logging.operations.get</code></li>
<li><code dir="ltr" translate="no">logging.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.settings.get</code></li>
<li><code dir="ltr" translate="no">logging.settings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.sinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.sinks.create</code></li>
<li><code dir="ltr" translate="no">logging.sinks.delete</code></li>
<li><code dir="ltr" translate="no">logging.sinks.get</code></li>
<li><code dir="ltr" translate="no">logging.sinks.list</code></li>
<li><code dir="ltr" translate="no">logging.sinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.sqlAlerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.sqlAlerts.create</code></li>
<li><code dir="ltr" translate="no">logging.sqlAlerts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.views.create</code></p>
<p><code dir="ltr" translate="no">logging.views.delete</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">logging.views.update</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.get</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.alerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.alerts.get</code></li>
<li><code dir="ltr" translate="no">monitoring.alerts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.get</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.services.get</code></p>
<p><code dir="ltr" translate="no">monitoring.services.list</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.get</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.list</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.get</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  update</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  addressGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  authzPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.locations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networksecurity.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.operations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  sacRealms.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacRealms.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.sacRealms.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  securityProfiles.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.urlLists.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  urlLists.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  urlLists.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.urlLists.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.urlLists.list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  urlLists.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.urlLists.use</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  agentGateways.  use</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  authzExtensions.  use</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.gateways.get</code></li>
<li><code dir="ltr" translate="no">networkservices.gateways.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.  gateways.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.gateways.use</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.grpcRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpFilters.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.httpRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpfilters.  use</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  createForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  deleteForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  getForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  listForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTcpExtensions.  updateForNetwork</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.locations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.locations.list</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.create</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  meshes.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.update</code></li>
<li><code dir="ltr" translate="no">networkservices.meshes.use</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.operations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  route_views.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  route_views.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceBindings.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.tcpRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.tlsRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">pubsub.*</code></p>
<ul>
<li><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.attach</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.commit</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.create</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.get</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.list</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.rollback</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.validate</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.create</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.get</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.list</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.seek</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.update</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.update</code></li>
<li><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.create</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.get</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.list</code></li>
<li><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.publish</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.update</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  createPeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  disableVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  enableVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p>
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
<td><h4 id="dataflow.jobs.cancel" class="permission-name add-link" data-text="dataflow.jobs.cancel" tabindex="-1"><code dir="ltr" translate="no">dataflow.jobs.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.jobs.create" class="permission-name add-link" data-text="dataflow.jobs.create" tabindex="-1"><code dir="ltr" translate="no">dataflow.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.jobs.get" class="permission-name add-link" data-text="dataflow.jobs.get" tabindex="-1"><code dir="ltr" translate="no">dataflow.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.jobs.list" class="permission-name add-link" data-text="dataflow.jobs.list" tabindex="-1"><code dir="ltr" translate="no">dataflow.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.jobs.snapshot" class="permission-name add-link" data-text="dataflow.jobs.snapshot" tabindex="-1"><code dir="ltr" translate="no">dataflow.jobs.snapshot</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.jobs.updateContents" class="permission-name add-link" data-text="dataflow.jobs.updateContents" tabindex="-1"><code dir="ltr" translate="no">dataflow.jobs.updateContents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.messages.list" class="permission-name add-link" data-text="dataflow.messages.list" tabindex="-1"><code dir="ltr" translate="no">dataflow.messages.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.metrics.get" class="permission-name add-link" data-text="dataflow.metrics.get" tabindex="-1"><code dir="ltr" translate="no">dataflow.metrics.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.shuffle.read" class="permission-name add-link" data-text="dataflow.shuffle.read" tabindex="-1"><code dir="ltr" translate="no">dataflow.shuffle.read</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.shuffle.write" class="permission-name add-link" data-text="dataflow.shuffle.write" tabindex="-1"><code dir="ltr" translate="no">dataflow.shuffle.write</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.snapshots.delete" class="permission-name add-link" data-text="dataflow.snapshots.delete" tabindex="-1"><code dir="ltr" translate="no">dataflow.snapshots.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.snapshots.get" class="permission-name add-link" data-text="dataflow.snapshots.get" tabindex="-1"><code dir="ltr" translate="no">dataflow.snapshots.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.snapshots.list" class="permission-name add-link" data-text="dataflow.snapshots.list" tabindex="-1"><code dir="ltr" translate="no">dataflow.snapshots.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.streamingWorkItems.ImportState" class="permission-name add-link" data-text="dataflow.streamingWorkItems.ImportState" tabindex="-1"><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  ImportState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.streamingWorkItems.commitWork" class="permission-name add-link" data-text="dataflow.streamingWorkItems.commitWork" tabindex="-1"><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  commitWork</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.streamingWorkItems.getData" class="permission-name add-link" data-text="dataflow.streamingWorkItems.getData" tabindex="-1"><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  getData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.streamingWorkItems.getWork" class="permission-name add-link" data-text="dataflow.streamingWorkItems.getWork" tabindex="-1"><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  getWork</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.streamingWorkItems.getWorkerMetadata" class="permission-name add-link" data-text="dataflow.streamingWorkItems.getWorkerMetadata" tabindex="-1"><code dir="ltr" translate="no">dataflow.  streamingWorkItems.  getWorkerMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.workItems.lease" class="permission-name add-link" data-text="dataflow.workItems.lease" tabindex="-1"><code dir="ltr" translate="no">dataflow.workItems.lease</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataflow.workItems.sendMessage" class="permission-name add-link" data-text="dataflow.workItems.sendMessage" tabindex="-1"><code dir="ltr" translate="no">dataflow.workItems.sendMessage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataflow.workItems.update" class="permission-name add-link" data-text="dataflow.workItems.update" tabindex="-1"><code dir="ltr" translate="no">dataflow.workItems.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.worker</code> )</p></td>
</tr>
</tbody>
</table>
