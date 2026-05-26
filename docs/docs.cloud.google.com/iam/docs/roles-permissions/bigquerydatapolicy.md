---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatapolicy
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatapolicy
title: BigQuery Data Policy roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Data Policy. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Data Policy roles

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
<td><h4 id="bigquerydatapolicy.admin" class="role-title add-link" data-text="BigQuery Data Policy Admin" tabindex="-1">BigQuery Data Policy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerydatapolicy.admin</code> )</p>
<p>Role for managing Data Policies in BigQuery</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code dir="ltr" translate="no">bigquery.dataPolicies.attach</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.create</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerydatapolicy.editor" class="role-title add-link" data-text="BigQuery Data Policy Editor" tabindex="-1">BigQuery Data Policy Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerydatapolicy.editor</code> )</p>
<p>Editor role for BigQuery Data Policy</p></td>
<td><p><code dir="ltr" translate="no">bigquery.bireservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.bireservations.get</code></li>
<li><code dir="ltr" translate="no">bigquery.bireservations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.config.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.config.get</code></li>
<li><code dir="ltr" translate="no">bigquery.config.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.connections.create</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.list</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.update</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.use</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.attach</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.create</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.update</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.  jobs.  createGlobalQuery</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  jobs.  listExecutionMetadata</code></p>
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
<p><code dir="ltr" translate="no">bigquery.reservations.create</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  listFailoverDatasets</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.update</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.use</code></p>
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
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.savedqueries.create</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.get</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.list</code></li>
<li><code dir="ltr" translate="no">bigquery.savedqueries.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.tables.createIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.replicateData</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.transfers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.transfers.get</code></li>
<li><code dir="ltr" translate="no">bigquery.transfers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerydatapolicy.viewer" class="role-title add-link" data-text="BigQuery Data Policy Viewer" tabindex="-1">BigQuery Data Policy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerydatapolicy.viewer</code> )</p>
<p>Role for viewing Data Policies in BigQuery</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code dir="ltr" translate="no">bigquery.dataPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerydatapolicy.maskedReader" class="role-title add-link" data-text="Masked Reader" tabindex="-1">Masked Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerydatapolicy.maskedReader</code> )</p>
<p>Masked read access to sub-resources tagged by the policy tag associated with a data policy, for example, BigQuery columns</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code dir="ltr" translate="no">bigquery.  dataPolicies.  maskedGet</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerydatapolicy.rawDataReader" class="role-title add-link" data-text="Raw Data Reader Beta" tabindex="-1">Raw Data Reader <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerydatapolicy.rawDataReader</code> )</p>
<p>Raw read access to sub-resources associated with a data policy, for example, BigQuery columns</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getRawData</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Data Policy permissions

There are no IAM permissions for this service.
