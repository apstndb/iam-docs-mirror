---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager
title: Cloud Deployment Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Deployment Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Deployment Manager roles

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
<td><h4 id="deploymentmanager.admin" class="role-title add-link" data-text="Deployment Manager Admin" tabindex="-1">Deployment Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p>Admin role for Deployment Manager.</p></td>
<td><p><code dir="ltr" translate="no">deploymentmanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  update</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  cancelPreview</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  stop</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.editor" class="role-title add-link" data-text="Deployment Manager Editor" tabindex="-1">Deployment Manager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p>Provides the permissions necessary to create and manage deployments.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  cancelPreview</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  stop</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.manifests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.types.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.types.create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.viewer" class="role-title add-link" data-text="Deployment Manager Viewer" tabindex="-1">Deployment Manager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p>Provides read-only access to all Deployment Manager-related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.manifests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.types.get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.types.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.typeEditor" class="role-title add-link" data-text="Deployment Manager Type Editor" tabindex="-1">Deployment Manager Type Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Provides read and write access to all Type Registry resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.types.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.types.create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.typeViewer" class="role-title add-link" data-text="Deployment Manager Type Viewer" tabindex="-1">Deployment Manager Type Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p>Provides read-only access to all Type Registry resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.types.get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.types.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
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
<td><h4 id="clouddeploymentmanager.serviceAgent" class="role-title add-link" data-text="Cloud Deployment Manager Service Agent" tabindex="-1">Cloud Deployment Manager Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</p>
<p>Allows Deployment Manager service to actuate resources across DM projects and folders</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  create</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  delete</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  update</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  create</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  delete</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></p>
<p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.operations.get</code></p>
<p><code dir="ltr" translate="no">appengine.services.update</code></p>
<p><code dir="ltr" translate="no">appengine.versions.create</code></p>
<p><code dir="ltr" translate="no">appengine.versions.delete</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.update</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.create</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.setCategory</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">bigtable.instances.create</code></p>
<p><code dir="ltr" translate="no">bigtable.instances.delete</code></p>
<p><code dir="ltr" translate="no">bigtable.instances.get</code></p>
<p><code dir="ltr" translate="no">bigtable.instances.update</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.create</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.delete</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.get</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.update</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  create</code></p>
<p><code dir="ltr" translate="no">billing.resourcebudgets.write</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.call</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  create</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  delete</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  update</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalog.  targets.  get</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.create</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.delete</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.get</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.update</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsql.databases.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsql.instances.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.delete</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.import</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.restart</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.update</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.delete</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.delete</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.create</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.delete</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.create</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.delete</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.get</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.update</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.create</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.delete</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.get</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.update</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.use</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.create</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.delete</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  setSecurityPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.update</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.use</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  addResourcePolicies</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  removeResourcePolicies</code></p>
<p><code dir="ltr" translate="no">compute.disks.resize</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.update</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  create</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  use</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscSetLabels</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  setTarget</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.update</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.use</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.use</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  create</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscCreate</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscDelete</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscSetLabels</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  attachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.create</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.delete</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.update</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  update</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  update</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.images.create</code></p>
<p><code dir="ltr" translate="no">compute.images.delete</code></p>
<p><code dir="ltr" translate="no">compute.images.deprecate</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.images.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.create</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.update</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.use</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  addAccessConfig</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteAccessConfig</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.instances.resume</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setDiskAutoDelete</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.start</code></p>
<p><code dir="ltr" translate="no">compute.instances.stop</code></p>
<p><code dir="ltr" translate="no">compute.instances.suspend</code></p>
<p><code dir="ltr" translate="no">compute.instances.update</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></p>
<p><code dir="ltr" translate="no">compute.instances.use</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.create</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.delete</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.use</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  attachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.create</code></p>
<p><code dir="ltr" translate="no">compute.networks.delete</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  switchToCustomMode</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.  organizations.  disableXpnResource</code></p>
<p><code dir="ltr" translate="no">compute.  organizations.  enableXpnHost</code></p>
<p><code dir="ltr" translate="no">compute.  organizations.  enableXpnResource</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  create</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  delete</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setUsageExportBucket</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  update</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  update</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  use</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.create</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.delete</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.use</code></p>
<p><code dir="ltr" translate="no">compute.regions.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.routers.create</code></p>
<p><code dir="ltr" translate="no">compute.routers.delete</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.update</code></p>
<p><code dir="ltr" translate="no">compute.routers.use</code></p>
<p><code dir="ltr" translate="no">compute.routes.create</code></p>
<p><code dir="ltr" translate="no">compute.routes.delete</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  update</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.create</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.delete</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.create</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.delete</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.create</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.delete</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  expandIpCidrRange</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.mirror</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.update</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslCertificates</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslPolicy</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.create</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.delete</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.get</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  addHealthCheck</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  addInstance</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.create</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.delete</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  removeHealthCheck</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  removeInstance</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  setSslCertificates</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.use</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.create</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.delete</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.update</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.use</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.create</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.delete</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.use</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.create</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.delete</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.get</code></p>
<p><code dir="ltr" translate="no">container.  backendConfigs.  create</code></p>
<p><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.get</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.bind</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.create</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.delete</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.create</code></p>
<p><code dir="ltr" translate="no">container.clusters.delete</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  getCredentials</code></p>
<p><code dir="ltr" translate="no">container.clusters.update</code></p>
<p><code dir="ltr" translate="no">container.configMaps.create</code></p>
<p><code dir="ltr" translate="no">container.configMaps.delete</code></p>
<p><code dir="ltr" translate="no">container.configMaps.get</code></p>
<p><code dir="ltr" translate="no">container.configMaps.update</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.create</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.delete</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.get</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.update</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.create</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.delete</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.get</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.update</code></p>
<p><code dir="ltr" translate="no">container.deployments.create</code></p>
<p><code dir="ltr" translate="no">container.deployments.delete</code></p>
<p><code dir="ltr" translate="no">container.deployments.get</code></p>
<p><code dir="ltr" translate="no">container.deployments.update</code></p>
<p><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></p>
<p><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></p>
<p><code dir="ltr" translate="no">container.frontendConfigs.get</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  create</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  delete</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></p>
<p><code dir="ltr" translate="no">container.ingresses.create</code></p>
<p><code dir="ltr" translate="no">container.ingresses.delete</code></p>
<p><code dir="ltr" translate="no">container.ingresses.get</code></p>
<p><code dir="ltr" translate="no">container.jobs.create</code></p>
<p><code dir="ltr" translate="no">container.jobs.delete</code></p>
<p><code dir="ltr" translate="no">container.jobs.get</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  create</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  delete</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  get</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  delete</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.namespaces.create</code></p>
<p><code dir="ltr" translate="no">container.namespaces.delete</code></p>
<p><code dir="ltr" translate="no">container.namespaces.get</code></p>
<p><code dir="ltr" translate="no">container.  networkPolicies.  create</code></p>
<p><code dir="ltr" translate="no">container.  networkPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">container.networkPolicies.get</code></p>
<p><code dir="ltr" translate="no">container.operations.get</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  create</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  delete</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">container.  priorityClasses.  create</code></p>
<p><code dir="ltr" translate="no">container.  priorityClasses.  delete</code></p>
<p><code dir="ltr" translate="no">container.priorityClasses.get</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  create</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  delete</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  get</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.create</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.delete</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.get</code></p>
<p><code dir="ltr" translate="no">container.roles.bind</code></p>
<p><code dir="ltr" translate="no">container.roles.create</code></p>
<p><code dir="ltr" translate="no">container.roles.delete</code></p>
<p><code dir="ltr" translate="no">container.roles.escalate</code></p>
<p><code dir="ltr" translate="no">container.roles.get</code></p>
<p><code dir="ltr" translate="no">container.roles.update</code></p>
<p><code dir="ltr" translate="no">container.secrets.create</code></p>
<p><code dir="ltr" translate="no">container.secrets.delete</code></p>
<p><code dir="ltr" translate="no">container.secrets.get</code></p>
<p><code dir="ltr" translate="no">container.secrets.update</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></p>
<p><code dir="ltr" translate="no">container.services.create</code></p>
<p><code dir="ltr" translate="no">container.services.delete</code></p>
<p><code dir="ltr" translate="no">container.services.get</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.create</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.delete</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.get</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.update</code></p>
<p><code dir="ltr" translate="no">container.  storageClasses.  create</code></p>
<p><code dir="ltr" translate="no">container.  storageClasses.  delete</code></p>
<p><code dir="ltr" translate="no">container.storageClasses.get</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  delete</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.get</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  create</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  get</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  use</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.create</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.delete</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.get</code></p>
<p><code dir="ltr" translate="no">dataproc.nodeGroups.create</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.get</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  create</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">dataproc.workflowTemplates.get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></p>
<p><code dir="ltr" translate="no">dns.changes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.changes.create</code></li>
<li><code dir="ltr" translate="no">dns.changes.get</code></li>
<li><code dir="ltr" translate="no">dns.changes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.update</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">dns.policies.delete</code></p>
<p><code dir="ltr" translate="no">dns.policies.get</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></p>
<p><code dir="ltr" translate="no">file.instances.create</code></p>
<p><code dir="ltr" translate="no">file.instances.delete</code></p>
<p><code dir="ltr" translate="no">file.instances.get</code></p>
<p><code dir="ltr" translate="no">file.instances.update</code></p>
<p><code dir="ltr" translate="no">file.operations.get</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebase.projects.update</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></p>
<p><code dir="ltr" translate="no">iam.roles.create</code></p>
<p><code dir="ltr" translate="no">iam.roles.delete</code></p>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.roles.update</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.delete</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.delete</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.update</code></p>
<p><code dir="ltr" translate="no">logging.buckets.update</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.create</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.delete</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.get</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.update</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.create</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.delete</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.update</code></p>
<p><code dir="ltr" translate="no">logging.  notificationRules.  create</code></p>
<p><code dir="ltr" translate="no">logging.sinks.create</code></p>
<p><code dir="ltr" translate="no">logging.sinks.delete</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.update</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.get</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  update</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.create</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.delete</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.update</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.create</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.delete</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.get</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.update</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  delete</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  delete</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  update</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  delete</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  update</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  use</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.attach</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">redis.instances.create</code></p>
<p><code dir="ltr" translate="no">redis.instances.delete</code></p>
<p><code dir="ltr" translate="no">redis.instances.get</code></p>
<p><code dir="ltr" translate="no">redis.instances.update</code></p>
<p><code dir="ltr" translate="no">redis.instances.updateAuth</code></p>
<p><code dir="ltr" translate="no">redis.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  createBillingAssignment</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  deleteBillingAssignment</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.move</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagHolds.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagHolds.  delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  associatePrivateZone</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">source.repos.create</code></p>
<p><code dir="ltr" translate="no">spanner.databaseOperations.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.create</code></p>
<p><code dir="ltr" translate="no">spanner.databases.drop</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.updateDdl</code></p>
<p><code dir="ltr" translate="no">spanner.instanceOperations.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.create</code></p>
<p><code dir="ltr" translate="no">spanner.instances.delete</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.update</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.hmacKeys.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.create</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.delete</code></p>
<p><code dir="ltr" translate="no">vpcaccess.operations.get</code></p>
<p><code dir="ltr" translate="no">workflows.operations.get</code></p>
<p><code dir="ltr" translate="no">workflows.workflows.create</code></p>
<p><code dir="ltr" translate="no">workflows.workflows.delete</code></p>
<p><code dir="ltr" translate="no">workflows.workflows.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Deployment Manager permissions

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
<td><h4 id="deploymentmanager.compositeTypes.create" class="permission-name add-link" data-text="deploymentmanager.compositeTypes.create" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.compositeTypes.delete" class="permission-name add-link" data-text="deploymentmanager.compositeTypes.delete" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.compositeTypes.get" class="permission-name add-link" data-text="deploymentmanager.compositeTypes.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.compositeTypes.list" class="permission-name add-link" data-text="deploymentmanager.compositeTypes.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.compositeTypes.update" class="permission-name add-link" data-text="deploymentmanager.compositeTypes.update" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.deployments.cancelPreview" class="permission-name add-link" data-text="deploymentmanager.deployments.cancelPreview" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  cancelPreview</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.deployments.create" class="permission-name add-link" data-text="deploymentmanager.deployments.create" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.deployments.delete" class="permission-name add-link" data-text="deploymentmanager.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.deployments.get" class="permission-name add-link" data-text="deploymentmanager.deployments.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.deployments.getIamPolicy" class="permission-name add-link" data-text="deploymentmanager.deployments.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.deployments.list" class="permission-name add-link" data-text="deploymentmanager.deployments.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.deployments.setIamPolicy" class="permission-name add-link" data-text="deploymentmanager.deployments.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.deployments.stop" class="permission-name add-link" data-text="deploymentmanager.deployments.stop" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.deployments.update" class="permission-name add-link" data-text="deploymentmanager.deployments.update" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.manifests.get" class="permission-name add-link" data-text="deploymentmanager.manifests.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.manifests.list" class="permission-name add-link" data-text="deploymentmanager.manifests.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.operations.get" class="permission-name add-link" data-text="deploymentmanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.operations.list" class="permission-name add-link" data-text="deploymentmanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.resources.get" class="permission-name add-link" data-text="deploymentmanager.resources.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  resources.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.resources.list" class="permission-name add-link" data-text="deploymentmanager.resources.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.typeProviders.create" class="permission-name add-link" data-text="deploymentmanager.typeProviders.create" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.typeProviders.delete" class="permission-name add-link" data-text="deploymentmanager.typeProviders.delete" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.typeProviders.get" class="permission-name add-link" data-text="deploymentmanager.typeProviders.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.typeProviders.getType" class="permission-name add-link" data-text="deploymentmanager.typeProviders.getType" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.typeProviders.list" class="permission-name add-link" data-text="deploymentmanager.typeProviders.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.typeProviders.listTypes" class="permission-name add-link" data-text="deploymentmanager.typeProviders.listTypes" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.typeProviders.update" class="permission-name add-link" data-text="deploymentmanager.typeProviders.update" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.types.create" class="permission-name add-link" data-text="deploymentmanager.types.create" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.types.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.types.delete" class="permission-name add-link" data-text="deploymentmanager.types.delete" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.types.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.types.get" class="permission-name add-link" data-text="deploymentmanager.types.get" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.types.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="deploymentmanager.types.list" class="permission-name add-link" data-text="deploymentmanager.types.list" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.types.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="deploymentmanager.types.update" class="permission-name add-link" data-text="deploymentmanager.types.update" tabindex="-1"><code dir="ltr" translate="no">deploymentmanager.types.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
