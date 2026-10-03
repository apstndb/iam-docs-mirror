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
<td>BigQuery Data Policy Admin
<p>( <code>roles/ bigquerydatapolicy.admin</code> )</p>
<p>Role for managing Data Policies in BigQuery</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code>bigquery.dataPolicies.attach</code></p>
<p><code>bigquery.dataPolicies.create</code></p>
<p><code>bigquery.dataPolicies.delete</code></p>
<p><code>bigquery.dataPolicies.get</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery. dataPolicies. setIamPolicy</code></p>
<p><code>bigquery.dataPolicies.update</code></p></td>
</tr>
<tr class="even">
<td>BigQuery Data Policy Editor
<p>( <code>roles/ bigquerydatapolicy.editor</code> )</p>
<p>Editor role for BigQuery Data Policy</p></td>
<td><p><code>bigquery.bireservations.*</code></p>
<ul>
<li><code>bigquery.bireservations.get</code></li>
<li><code>bigquery.bireservations.update</code></li>
</ul>
<p><code>bigquery. capacityCommitments. get</code></p>
<p><code>bigquery. capacityCommitments. list</code></p>
<p><code>bigquery. capacityCommitments. update</code></p>
<p><code>bigquery.config.*</code></p>
<ul>
<li><code>bigquery.config.get</code></li>
<li><code>bigquery.config.update</code></li>
</ul>
<p><code>bigquery.connections.create</code></p>
<p><code>bigquery.connections.delete</code></p>
<p><code>bigquery.connections.get</code></p>
<p><code>bigquery. connections. getIamPolicy</code></p>
<p><code>bigquery.connections.list</code></p>
<p><code>bigquery.connections.update</code></p>
<p><code>bigquery.connections.updateTag</code></p>
<p><code>bigquery.connections.use</code></p>
<p><code>bigquery.dataPolicies.attach</code></p>
<p><code>bigquery.dataPolicies.create</code></p>
<p><code>bigquery.dataPolicies.delete</code></p>
<p><code>bigquery.dataPolicies.get</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery.dataPolicies.update</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery. datasets. listEffectiveTags</code></p>
<p><code>bigquery. datasets. listTagBindings</code></p>
<p><code>bigquery.datasets.updateTag</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery. jobs. createGlobalQuery</code></p>
<p><code>bigquery.jobs.delete</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery. jobs. listExecutionMetadata</code></p>
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
<p><code>bigquery.reservations.create</code></p>
<p><code>bigquery.reservations.delete</code></p>
<p><code>bigquery.reservations.get</code></p>
<p><code>bigquery. reservations. getIamPolicy</code></p>
<p><code>bigquery.reservations.list</code></p>
<p><code>bigquery. reservations. listFailoverDatasets</code></p>
<p><code>bigquery.reservations.update</code></p>
<p><code>bigquery.reservations.use</code></p>
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
<p><code>bigquery. rowAccessPolicies. update</code></p>
<p><code>bigquery.savedqueries.*</code></p>
<ul>
<li><code>bigquery.savedqueries.create</code></li>
<li><code>bigquery.savedqueries.delete</code></li>
<li><code>bigquery.savedqueries.get</code></li>
<li><code>bigquery.savedqueries.list</code></li>
<li><code>bigquery.savedqueries.update</code></li>
</ul>
<p><code>bigquery.tables.createIndex</code></p>
<p><code>bigquery.tables.createSnapshot</code></p>
<p><code>bigquery.tables.deleteIndex</code></p>
<p><code>bigquery.tables.getIamPolicy</code></p>
<p><code>bigquery. tables. listEffectiveTags</code></p>
<p><code>bigquery. tables. listTagBindings</code></p>
<p><code>bigquery.tables.replicateData</code></p>
<p><code>bigquery. tables. restoreSnapshot</code></p>
<p><code>bigquery.tables.updateIndex</code></p>
<p><code>bigquery.transfers.*</code></p>
<ul>
<li><code>bigquery.transfers.get</code></li>
<li><code>bigquery.transfers.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>BigQuery Data Policy Viewer
<p>( <code>roles/ bigquerydatapolicy.viewer</code> )</p>
<p>Role for viewing Data Policies in BigQuery</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code>bigquery.dataPolicies.get</code></p>
<p><code>bigquery.dataPolicies.list</code></p></td>
</tr>
<tr class="even">
<td>Masked Reader
<p>( <code>roles/ bigquerydatapolicy.maskedReader</code> )</p>
<p>Masked read access to sub-resources tagged by the policy tag associated with a data policy, for example, BigQuery columns</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code>bigquery. dataPolicies. maskedGet</code></p></td>
</tr>
<tr class="odd">
<td>Raw Data Reader <sup>Beta</sup>
<p>( <code>roles/ bigquerydatapolicy.rawDataReader</code> )</p>
<p>Raw read access to sub-resources associated with a data policy, for example, BigQuery columns</p>
<p>This role can only be granted on Resource Manager resources (projects, folders, and organizations).</p></td>
<td><p><code>bigquery. dataPolicies. getRawData</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Data Policy permissions

There are no IAM permissions for this service.
