---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/fleetengine
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine
title: FleetEngine roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for FleetEngine. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## FleetEngine roles

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
<td><h4 id="fleetengine.consumerSdkUser" class="role-title add-link" data-text="Fleet Engine Consumer SDK User" tabindex="-1">Fleet Engine Consumer SDK User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.consumerSdkUser</code> )</p>
<p>Limited read access to Fleet Engine resources</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.trips.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.search</code></p>
<p><code dir="ltr" translate="no">fleetengine.  vehicles.  searchFuzzed</code></p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryAdmin" class="role-title add-link" data-text="Fleet Engine Delivery Admin" tabindex="-1">Fleet Engine Delivery Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p>Full access to Fleet Engine Delivery resources.</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.deliveryvehicles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  allowAllActions</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  create</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  delete</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  get</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  list</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  update</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateLocation</code></li>
<li><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateVehicleStops</code></li>
</ul>
<p><code dir="ltr" translate="no">fleetengine.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">fleetengine.  tasks.  allowAllActions</code></li>
<li><code dir="ltr" translate="no">fleetengine.tasks.create</code></li>
<li><code dir="ltr" translate="no">fleetengine.tasks.delete</code></li>
<li><code dir="ltr" translate="no">fleetengine.tasks.get</code></li>
<li><code dir="ltr" translate="no">fleetengine.tasks.list</code></li>
<li><code dir="ltr" translate="no">fleetengine.  tasks.  searchWithTrackingId</code></li>
<li><code dir="ltr" translate="no">fleetengine.tasks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">fleetengine.tasktrackinginfo.*</code></p>
<ul>
<li><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  allowAllActions</code></li>
<li><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.deliveryConsumer" class="role-title add-link" data-text="Fleet Engine Delivery Consumer User" tabindex="-1">Fleet Engine Delivery Consumer User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.deliveryConsumer</code> )</p>
<p>Limited read access to Fleet Engine Delivery resources</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.  tasks.  searchWithTrackingId</code></p>
<p><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryFleetReader" class="role-title add-link" data-text="Fleet Engine Delivery Fleet Reader User" tabindex="-1">Fleet Engine Delivery Fleet Reader User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p>Grants read access to all Fleet Engine Delivery resources</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  get</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  list</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.list</code></p>
<p><code dir="ltr" translate="no">fleetengine.  tasks.  searchWithTrackingId</code></p>
<p><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.deliverySuperUser" class="role-title add-link" data-text="Fleet Engine Delivery Super User" tabindex="-1">Fleet Engine Delivery Super User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p>Full access to Fleet Engine DeliveryVehicles and Tasks resources.</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  create</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  delete</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  get</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  list</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  update</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateLocation</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateVehicleStops</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.create</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.delete</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.list</code></p>
<p><code dir="ltr" translate="no">fleetengine.  tasks.  searchWithTrackingId</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.update</code></p>
<p><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryTrustedDriver" class="role-title add-link" data-text="Fleet Engine Delivery Trusted Driver User" tabindex="-1">Fleet Engine Delivery Trusted Driver User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p>
<p>Read and write access to Fleet Engine Delivery resources</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  create</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  get</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  update</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateLocation</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateVehicleStops</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.create</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.deliveryUntrustedDriver" class="role-title add-link" data-text="Fleet Engine Delivery Untrusted Driver User" tabindex="-1">Fleet Engine Delivery Untrusted Driver User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.deliveryUntrustedDriver</code> )</p>
<p>Limited write access to Fleet Engine Delivery Vehicle resources</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  get</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateLocation</code></p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.driverSdkUser" class="role-title add-link" data-text="Fleet Engine Driver SDK User" tabindex="-1">Fleet Engine Driver SDK User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.driverSdkUser</code> )</p>
<p>Read and limited update access to Fleet Engine resources</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.trips.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.search</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.update</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.  vehicles.  updateLocation</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.ondemandAdmin" class="role-title add-link" data-text="Fleet Engine On-Demand Admin" tabindex="-1">Fleet Engine On-Demand Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p>Full access to Vehicle and Trip resources.</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.trips.*</code></p>
<ul>
<li><code dir="ltr" translate="no">fleetengine.  trips.  allowAllActions</code></li>
<li><code dir="ltr" translate="no">fleetengine.trips.create</code></li>
<li><code dir="ltr" translate="no">fleetengine.trips.delete</code></li>
<li><code dir="ltr" translate="no">fleetengine.trips.get</code></li>
<li><code dir="ltr" translate="no">fleetengine.trips.search</code></li>
<li><code dir="ltr" translate="no">fleetengine.trips.update</code></li>
<li><code dir="ltr" translate="no">fleetengine.trips.updateState</code></li>
</ul>
<p><code dir="ltr" translate="no">fleetengine.vehicles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">fleetengine.  vehicles.  allowAllActions</code></li>
<li><code dir="ltr" translate="no">fleetengine.vehicles.create</code></li>
<li><code dir="ltr" translate="no">fleetengine.vehicles.delete</code></li>
<li><code dir="ltr" translate="no">fleetengine.vehicles.get</code></li>
<li><code dir="ltr" translate="no">fleetengine.vehicles.list</code></li>
<li><code dir="ltr" translate="no">fleetengine.vehicles.search</code></li>
<li><code dir="ltr" translate="no">fleetengine.  vehicles.  searchFuzzed</code></li>
<li><code dir="ltr" translate="no">fleetengine.vehicles.update</code></li>
<li><code dir="ltr" translate="no">fleetengine.  vehicles.  updateLocation</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.serviceSuperUser" class="role-title add-link" data-text="Fleet Engine Service Super User" tabindex="-1">Fleet Engine Service Super User</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p>Full access to all Fleet Engine resources.</p></td>
<td><p><code dir="ltr" translate="no">fleetengine.trips.create</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.delete</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.search</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.update</code></p>
<p><code dir="ltr" translate="no">fleetengine.trips.updateState</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.create</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.delete</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.get</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.list</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.search</code></p>
<p><code dir="ltr" translate="no">fleetengine.  vehicles.  searchFuzzed</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.update</code></p>
<p><code dir="ltr" translate="no">fleetengine.  vehicles.  updateLocation</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="fleetengine.serviceAgent" class="role-title add-link" data-text="FleetEngine Service Agent" tabindex="-1">FleetEngine Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</p>
<p>Grants the FleetEngine Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p></td>
</tr>
</tbody>
</table>

## FleetEngine permissions

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
<td><h4 id="fleetengine.deliveryvehicles.allowAllActions" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.allowAllActions" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  allowAllActions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryvehicles.create" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.create" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.deliveryvehicles.delete" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.delete" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryvehicles.get" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.get" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryFleetReader">Fleet Engine Delivery Fleet Reader User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryUntrustedDriver">Fleet Engine Delivery Untrusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryUntrustedDriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.deliveryvehicles.list" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.list" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryFleetReader">Fleet Engine Delivery Fleet Reader User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryvehicles.update" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.update" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.deliveryvehicles.updateLocation" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.updateLocation" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateLocation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryUntrustedDriver">Fleet Engine Delivery Untrusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryUntrustedDriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.deliveryvehicles.updateVehicleStops" class="permission-name add-link" data-text="fleetengine.deliveryvehicles.updateVehicleStops" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  updateVehicleStops</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.tasks.allowAllActions" class="permission-name add-link" data-text="fleetengine.tasks.allowAllActions" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  tasks.  allowAllActions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.tasks.create" class="permission-name add-link" data-text="fleetengine.tasks.create" tabindex="-1"><code dir="ltr" translate="no">fleetengine.tasks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.tasks.delete" class="permission-name add-link" data-text="fleetengine.tasks.delete" tabindex="-1"><code dir="ltr" translate="no">fleetengine.tasks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.tasks.get" class="permission-name add-link" data-text="fleetengine.tasks.get" tabindex="-1"><code dir="ltr" translate="no">fleetengine.tasks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryFleetReader">Fleet Engine Delivery Fleet Reader User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.tasks.list" class="permission-name add-link" data-text="fleetengine.tasks.list" tabindex="-1"><code dir="ltr" translate="no">fleetengine.tasks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryFleetReader">Fleet Engine Delivery Fleet Reader User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.tasks.searchWithTrackingId" class="permission-name add-link" data-text="fleetengine.tasks.searchWithTrackingId" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  tasks.  searchWithTrackingId</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryConsumer">Fleet Engine Delivery Consumer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryFleetReader">Fleet Engine Delivery Fleet Reader User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.tasks.update" class="permission-name add-link" data-text="fleetengine.tasks.update" tabindex="-1"><code dir="ltr" translate="no">fleetengine.tasks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryTrustedDriver">Fleet Engine Delivery Trusted Driver User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryTrustedDriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.tasktrackinginfo.allowAllActions" class="permission-name add-link" data-text="fleetengine.tasktrackinginfo.allowAllActions" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  allowAllActions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.tasktrackinginfo.get" class="permission-name add-link" data-text="fleetengine.tasktrackinginfo.get" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  tasktrackinginfo.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryConsumer">Fleet Engine Delivery Consumer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryFleetReader">Fleet Engine Delivery Fleet Reader User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryFleetReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.trips.allowAllActions" class="permission-name add-link" data-text="fleetengine.trips.allowAllActions" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  trips.  allowAllActions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.trips.create" class="permission-name add-link" data-text="fleetengine.trips.create" tabindex="-1"><code dir="ltr" translate="no">fleetengine.trips.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.trips.delete" class="permission-name add-link" data-text="fleetengine.trips.delete" tabindex="-1"><code dir="ltr" translate="no">fleetengine.trips.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.trips.get" class="permission-name add-link" data-text="fleetengine.trips.get" tabindex="-1"><code dir="ltr" translate="no">fleetengine.trips.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.consumerSdkUser">Fleet Engine Consumer SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.consumerSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.driverSdkUser">Fleet Engine Driver SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.driverSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.trips.search" class="permission-name add-link" data-text="fleetengine.trips.search" tabindex="-1"><code dir="ltr" translate="no">fleetengine.trips.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.driverSdkUser">Fleet Engine Driver SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.driverSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.trips.update" class="permission-name add-link" data-text="fleetengine.trips.update" tabindex="-1"><code dir="ltr" translate="no">fleetengine.trips.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.driverSdkUser">Fleet Engine Driver SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.driverSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.trips.updateState" class="permission-name add-link" data-text="fleetengine.trips.updateState" tabindex="-1"><code dir="ltr" translate="no">fleetengine.trips.updateState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.vehicles.allowAllActions" class="permission-name add-link" data-text="fleetengine.vehicles.allowAllActions" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  vehicles.  allowAllActions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.vehicles.create" class="permission-name add-link" data-text="fleetengine.vehicles.create" tabindex="-1"><code dir="ltr" translate="no">fleetengine.vehicles.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.vehicles.delete" class="permission-name add-link" data-text="fleetengine.vehicles.delete" tabindex="-1"><code dir="ltr" translate="no">fleetengine.vehicles.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.vehicles.get" class="permission-name add-link" data-text="fleetengine.vehicles.get" tabindex="-1"><code dir="ltr" translate="no">fleetengine.vehicles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.consumerSdkUser">Fleet Engine Consumer SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.consumerSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.driverSdkUser">Fleet Engine Driver SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.driverSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.vehicles.list" class="permission-name add-link" data-text="fleetengine.vehicles.list" tabindex="-1"><code dir="ltr" translate="no">fleetengine.vehicles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.vehicles.search" class="permission-name add-link" data-text="fleetengine.vehicles.search" tabindex="-1"><code dir="ltr" translate="no">fleetengine.vehicles.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.consumerSdkUser">Fleet Engine Consumer SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.consumerSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.vehicles.searchFuzzed" class="permission-name add-link" data-text="fleetengine.vehicles.searchFuzzed" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  vehicles.  searchFuzzed</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.consumerSdkUser">Fleet Engine Consumer SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.consumerSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fleetengine.vehicles.update" class="permission-name add-link" data-text="fleetengine.vehicles.update" tabindex="-1"><code dir="ltr" translate="no">fleetengine.vehicles.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fleetengine.vehicles.updateLocation" class="permission-name add-link" data-text="fleetengine.vehicles.updateLocation" tabindex="-1"><code dir="ltr" translate="no">fleetengine.  vehicles.  updateLocation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.driverSdkUser">Fleet Engine Driver SDK User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.driverSdkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p></td>
</tr>
</tbody>
</table>
