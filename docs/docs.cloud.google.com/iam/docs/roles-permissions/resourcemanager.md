---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager
title: Resource Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Resource Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Resource Manager roles

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
<td><h4 id="resourcemanager.folderAdmin" class="role-title add-link" data-text="Folder Admin" tabindex="-1">Folder Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p>Provides all available permissions for working with folders.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  create</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  delete</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  send</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.capabilities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  capabilities.  get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  capabilities.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.folders.create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.folders.delete</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.folders.get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.folders.list</code></li>
<li><code dir="ltr" translate="no">resourcemanager.folders.move</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  undelete</code></li>
<li><code dir="ltr" translate="no">resourcemanager.folders.update</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  folders.  updatePolicyBinding</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  createPolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  deletePolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.move</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updatePolicyBinding</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.organizationAdmin" class="role-title add-link" data-text="Organization Administrator" tabindex="-1">Organization Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p>Access to manage IAM policies and view organization policies for organizations, folders, and projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  create</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  delete</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  send</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.capabilities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  capabilities.  get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  capabilities.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  createPolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  deletePolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  updatePolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  organizations.  updatePolicyBinding</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  createPolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  deletePolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updatePolicyBinding</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projectIamAdmin" class="role-title add-link" data-text="Project IAM Admin" tabindex="-1">Project IAM Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p>Provides permissions to administer allow policies on projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  createPolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  deletePolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updatePolicyBinding</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projectMover" class="role-title add-link" data-text="Project Mover" tabindex="-1">Project Mover</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.projectMover</code> )</p>
<p>Provides access to update and move projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.move</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagAdmin" class="role-title add-link" data-text="Tag Administrator" tabindex="-1">Tag Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Access to create, delete, update, and manage access to Tags</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.tagHolds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagHolds.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagHolds.  delete</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.tagKeys.create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagKeys.delete</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagKeys.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagKeys.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagKeys.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValues.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValues.  delete</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValues.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValues.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValues.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagUser" class="role-title add-link" data-text="Tag User" tabindex="-1">Tag User</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p>Access to list Tags and manage their associations with resources</p></td>
<td><p><code dir="ltr" translate="no">alloydb.  backups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.apis.createTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.apis.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.disks.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.images.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.migrationJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">dns.policies.createTagBinding</code></p>
<p><code dir="ltr" translate="no">dns.policies.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">dns.policies.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">dns.policies.listTagBindings</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.backups.createTagBinding</code></p>
<p><code dir="ltr" translate="no">file.backups.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.backups.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">file.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.instances.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  gateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.createTagBinding</code></p>
<p><code dir="ltr" translate="no">run.jobs.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.createTagBinding</code></p>
<p><code dir="ltr" translate="no">run.services.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagViewer" class="role-title add-link" data-text="Tag Viewer" tabindex="-1">Tag Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p>Access to list Tags and their associations with resources</p></td>
<td><p><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.disks.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.images.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">dns.policies.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">dns.policies.listTagBindings</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.backups.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.instances.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folderCreator" class="role-title add-link" data-text="Folder Creator" tabindex="-1">Folder Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p>Provides permissions needed to browse the hierarchy and create folders.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></p>
<p><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  capabilities.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folderEditor" class="role-title add-link" data-text="Folder Editor" tabindex="-1">Folder Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p>Provides permission to modify folders as well as to view a folder's allow policy.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></p>
<p><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.capabilities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  capabilities.  get</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  capabilities.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  undelete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folderIamAdmin" class="role-title add-link" data-text="Folder IAM Admin" tabindex="-1">Folder IAM Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p>
<p>Provides permissions to administer allow policies on folders.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  createPolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  deletePolicyBinding</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  updatePolicyBinding</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folderMover" class="role-title add-link" data-text="Folder Mover" tabindex="-1">Folder Mover</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.folderMover</code> )</p>
<p>Provides permission to move projects and folders into and out of a parent organization or folder.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.move</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.move</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folderViewer" class="role-title add-link" data-text="Folder Viewer" tabindex="-1">Folder Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p>
<p>Provides permission to get a folder and list the folders and projects below a resource.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></p>
<p><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  capabilities.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.lienModifier" class="role-title add-link" data-text="Project Lien Modifier" tabindex="-1">Project Lien Modifier</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.lienModifier</code> )</p>
<p>Provides access to modify Liens on projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.organizationViewer" class="role-title add-link" data-text="Organization Viewer" tabindex="-1">Organization Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.organizationViewer</code> )</p>
<p>Provides access to view an organization.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projectCreator" class="role-title add-link" data-text="Project Creator" tabindex="-1">Project Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.projectCreator</code> )</p>
<p>Provides access to create new projects. Once a user creates a project, they're automatically granted the owner role for that project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  create</code></p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projectDeleter" class="role-title add-link" data-text="Project Deleter" tabindex="-1">Project Deleter</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.projectDeleter</code> )</p>
<p>Provides access to delete Google Cloud projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  projects.  delete</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagHoldAdmin" class="role-title add-link" data-text="Tag Hold Administrator" tabindex="-1">Tag Hold Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcemanager.tagHoldAdmin</code> )</p>
<p>Access to create, delete and list TagHolds under a TagValue</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.tagHolds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagHolds.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagHolds.  delete</code></li>
<li><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Resource Manager permissions

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
<td><h4 id="resourcemanager.capabilities.get" class="permission-name add-link" data-text="resourcemanager.capabilities.get" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  capabilities.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.capabilities.update" class="permission-name add-link" data-text="resourcemanager.capabilities.update" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  capabilities.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.create" class="permission-name add-link" data-text="resourcemanager.folders.create" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.folders.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folders.createPolicyBinding" class="permission-name add-link" data-text="resourcemanager.folders.createPolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  createPolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.delete" class="permission-name add-link" data-text="resourcemanager.folders.delete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.folders.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folders.deletePolicyBinding" class="permission-name add-link" data-text="resourcemanager.folders.deletePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  deletePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.get" class="permission-name add-link" data-text="resourcemanager.folders.get" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.folders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.folderServiceAgent">Privileged Access Manager Folder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.folderServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folders.getIamPolicy" class="permission-name add-link" data-text="resourcemanager.folders.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.folderServiceAgent">Privileged Access Manager Folder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.folderServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.list" class="permission-name add-link" data-text="resourcemanager.folders.list" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.folders.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folders.move" class="permission-name add-link" data-text="resourcemanager.folders.move" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.folders.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderMover">Folder Mover</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderMover</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.searchPolicyBindings" class="permission-name add-link" data-text="resourcemanager.folders.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folders.setIamPolicy" class="permission-name add-link" data-text="resourcemanager.folders.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.folderServiceAgent">Privileged Access Manager Folder Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.folderServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.undelete" class="permission-name add-link" data-text="resourcemanager.folders.undelete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.folders.update" class="permission-name add-link" data-text="resourcemanager.folders.update" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.folders.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.folders.updatePolicyBinding" class="permission-name add-link" data-text="resourcemanager.folders.updatePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  folders.  updatePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.hierarchyNodes.createTagBinding" class="permission-name add-link" data-text="resourcemanager.hierarchyNodes.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.hierarchyNodes.deleteTagBinding" class="permission-name add-link" data-text="resourcemanager.hierarchyNodes.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.hierarchyNodes.listEffectiveTags" class="permission-name add-link" data-text="resourcemanager.hierarchyNodes.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.hierarchyNodes.listTagBindings" class="permission-name add-link" data-text="resourcemanager.hierarchyNodes.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.organizations.createPolicyBinding" class="permission-name add-link" data-text="resourcemanager.organizations.createPolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  createPolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.organizations.deletePolicyBinding" class="permission-name add-link" data-text="resourcemanager.organizations.deletePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  deletePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.organizations.get" class="permission-name add-link" data-text="resourcemanager.organizations.get" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  axt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.editor">Cloud BeyondCorp Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.viewer">Cloud BeyondCorp Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.subscriptionAdmin">Cloud BeyondCorp Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.subscriptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.subscriptionViewer">Cloud BeyondCorp Subscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.subscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.creator">Billing Account Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.creator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationViewer">Organization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectCreator">Project Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesEditor">Security Center Sources Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesViewer">Security Center Sources Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeploymentsViewer">Security Posture Deployments Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeploymentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureViewer">Security Posture Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.quotaAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ciem#ciem.serviceAgent">CIEM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ciem.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.organizations.getIamPolicy" class="permission-name add-link" data-text="resourcemanager.organizations.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.organizations.searchPolicyBindings" class="permission-name add-link" data-text="resourcemanager.organizations.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.organizations.setIamPolicy" class="permission-name add-link" data-text="resourcemanager.organizations.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.organizations.updatePolicyBinding" class="permission-name add-link" data-text="resourcemanager.organizations.updatePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  organizations.  updatePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.create" class="permission-name add-link" data-text="resourcemanager.projects.create" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectCreator">Project Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.createBillingAssignment" class="permission-name add-link" data-text="resourcemanager.projects.createBillingAssignment" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  createBillingAssignment</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectManager">Project Billing Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.projectManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.createPolicyBinding" class="permission-name add-link" data-text="resourcemanager.projects.createPolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  createPolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.delete" class="permission-name add-link" data-text="resourcemanager.projects.delete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectDeleter">Project Deleter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectDeleter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.deleteBillingAssignment" class="permission-name add-link" data-text="resourcemanager.projects.deleteBillingAssignment" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  deleteBillingAssignment</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectManager">Project Billing Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.projectManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.deletePolicyBinding" class="permission-name add-link" data-text="resourcemanager.projects.deletePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  deletePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.get" class="permission-name add-link" data-text="resourcemanager.projects.get" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.projects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.admin">Agent Platform Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.editor">Aiplatform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user">Agent Platform User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.viewer">Agent Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.admin">Androidmanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  androidmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.viewer">Apigee Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.viewer">Apigeeconnect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.admin">Cloud Apigee Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.editor">Cloud Apigee Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.viewer">Cloud Apigee Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer">Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor">Assured OSS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer">Assured OSS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  axt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin">Batch Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer">Batch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.admin">Cloud BeyondCorp Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.editor">Cloud BeyondCorp Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.viewer">Cloud BeyondCorp Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.metadataViewer">BigQuery Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.readSessionUser">BigQuery Read Session User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.readSessionUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceAdmin">BigQuery Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.resourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceEditor">BigQuery Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.resourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceViewer">BigQuery Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.resourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatapolicy#bigquerydatapolicy.editor">BigQuery Data Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatapolicy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.user">Bigtable User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.viewer">Bigtable Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.admin">Carestudio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.viewer">Care Studio Patients Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin">Chat Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.viewer">Chat Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.editor">Chronicle API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.viewer">Chronicle API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin">Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer">Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.admin">Gemini for Google Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.editor">Gemini for Google Cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.user">Gemini for Google Cloud User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.viewer">Gemini for Google Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.admin">Cloud Build Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.editor">Cloud Build Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.viewer">Cloud Build Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.admin">Cloudprivatecatalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.viewer">Cloudprivatecatalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.viewer">Cloud Profiler Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.viewer">Cloud Quotas Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.admin">Commerce Organization Governance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.viewer">Commerce Organization Governance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.admin">Commerce Producer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.viewer">Commerce Producer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer">Confidentialcomputing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterViewer">Kubernetes Engine Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.clusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.developer">Kubernetes Engine Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.editor">Kubernetes Engine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.viewer">Kubernetes Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.admin">Database Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasecenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.viewer">Database Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasecenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.editor">Databasesconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.viewer">Databasesconsole Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.admin">Data pipelines Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.viewer">Data pipelines Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.viewer">Dataproc Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.admin">Dataproc Resource Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocrm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.viewer">Dataproc Resource Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocrm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.viewer">Data Studio Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.editor">Discovery Engine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.viewer">Discovery Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.admin">Earth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.viewer">Earth Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.admin">Enterprise Purchasing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterprisepurchasing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.editor">Enterprise Purchasing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterprisepurchasing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.viewer">Enterprise Purchasing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterprisepurchasing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.admin">Eventarc Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.editor">Eventarc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.viewer">Eventarc Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.admin">Firebase App Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.viewer">Firebase App Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.admin">Firebase Data Connect API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.viewer">Firebase Data Connect API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.admin">Firebase Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.viewer">Firebase Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.viewer">Cloud Storage for Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.admin">Firebase AI Logic Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasevertexai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.viewer">Firebase AI Logic Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasevertexai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.viewer">Kubernetesmetadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer">Cloud Life Sciences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.admin">Logging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.privateLogViewer">Private Logs Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.privateLogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.viewer">Logs Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.admin">Google Cloud Managed Lustre Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lustre.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.viewer">Google Cloud Managed Lustre Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lustre.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.admin">MCP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mcp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser">MCP Tool User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mcp.toolUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.viewer">Memorystore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memorystore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer">Nestconsole Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.editor">Network Connectivity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.admin">Networksecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.editor">Networksecurity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.viewer">Networksecurity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.admin">Network Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.editor">Network Services Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.viewer">Network Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ondemandscanning#ondemandscanning.viewer">On-Demand Scanning Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ondemandscanning.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.admin">Opsconfigmonitoring Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  opsconfigmonitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.viewer">Opsconfigmonitoring Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  opsconfigmonitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.admin">Publicca Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  publicca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer">Subscription Linking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.admin">Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.editor">Recommender Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.viewer">Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.editor">Cloud Memorystore Redis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.viewer">Cloud Memorystore Redis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectMover">Project Mover</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer">Route Optimization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig#saasconfig.viewer">SaaS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretAccessor">Secret Manager Secret Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.admin">Servicehealth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicehealth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.viewer">Personalized Service Health Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicehealth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.viewer">Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.viewer">Stackdriver Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.admin">Storage Batch Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagebatchoperations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.viewer">Storage Batch Operations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagebatchoperations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.admin">Subscribewithgoogledeveloper Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  subscribewithgoogledeveloper.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.viewer">Subscribewithgoogledeveloper Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  subscribewithgoogledeveloper.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.editor">Telemetry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.admin">TPU Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  tpu.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.viewer">TPU Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  tpu.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.viewer">Trafficdirector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer">Translation Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin">Visual Inspection AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.entityTypeOwner">Agent Platform Feature Store EntityType owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.entityTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreAdmin">Agent Platform Feature Store Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataViewer">Agent Platform Feature Store Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataWriter">Agent Platform Feature Store Data Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreResourceViewer">Agent Platform Feature Store Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreResourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreUser">Agent Platform Feature Store User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsEditor">Apigee Analytics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.analyticsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsViewer">Apigee Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.developerAdmin">Apigee Developer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.developerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.environmentAdmin">Apigee Environment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.environmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.monetizationAdmin">Apigee Monetization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.monetizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.portalAdmin">Apigee Portal Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.portalAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.spaceConsoleUser">Apigee Space Console User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.spaceConsoleUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.worker">Cloud Apigee Registry Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appCreator">App Engine Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver">Appliance troubleshooting commands approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.troubleshooter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.predictor">AutoML Predictor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.predictor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor">Batch Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer">Batch Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor">Batch ResourceAllowance Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.resourceAllowancesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer">Batch ResourceAllowance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.resourceAllowancesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.reader">Bigtable Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.dataGovernor">Chronicle API Data Governor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.dataGovernor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationAdmin">Chronicle API Federation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.federationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationViewer">Chronicle API Federation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.federationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.limitedViewer">Chronicle API Limited Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.limitedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.restrictedDataAccessViewer">Chronicle API Restricted Data Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.restrictedDataAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarRemoteAgent">Chronicle SOAR Remote Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarRemoteAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesAdmin">Code Repository Indexes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeRepositoryIndexesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesViewer">Code Repository Indexes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeRepositoryIndexesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.approver">Cloud Build Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.editor">Cloud Build Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.viewer">Cloud Build Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionAdmin">Cloud Build Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.connectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionViewer">Cloud Build Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.connectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsEditor">Cloud Build Integrations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.integrationsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsOwner">Cloud Build Integrations Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.integrationsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsViewer">Cloud Build Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.integrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolEditor">Cloud Build WorkerPool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.workerPoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolOwner">Cloud Build WorkerPool Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.workerPoolOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolViewer">Cloud Build WorkerPool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.workerPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.consumer">Catalog Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportEditor">Advisory Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.advisorySupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportViewer">Advisory Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.advisorySupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.enqueuer">Cloud Tasks Enqueuer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.enqueuer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskDeleter">Cloud Tasks Task Deleter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskRunner">Cloud Tasks Task Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigViewer">Commerce Business Enablement PaymentConfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.user">Governed Marketplace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer">Commerce Price Management Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.publicIpAdmin">Compute Public IP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.publicIpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyAdmin">Compute VM extension policy admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.vmExtensionPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyViewer">Compute VM extension policy viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.vmExtensionPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.viewer">Container Analysis Notes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.viewer">Container Analysis Occurrences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryAdmin">Studio Query Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.studioQueryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryUser">Studio Query User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.studioQueryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.invoker">Data pipelines Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessViewer">Dataproc Serverless Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceEditor">Gemini Enterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceRestrictedUser">Gemini Enterprise Restricted User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceRestrictedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceViewer">Gemini Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmOwner">Cloud NotebookLM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.notebookLmOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmUser">Cloud NotebookLM User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.notebookLmUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsAdmin">Earth Subscriptions Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsViewer">Earth Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.subscriptionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.offlineCredentialUser">Edge Container Cluster offline Credential User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.offlineCredentialUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.connectionPublisher">Eventarc Connection Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.connectionPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.developer">Eventarc Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.publisher">Eventarc Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.developer">Firebase App Hosting Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrash.symbolMappingsAdmin">Firebase Crash Symbol Uploader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrash.symbolMappingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.certificateViewer">Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.certificateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.issuerParticipantsAdmin">Issuerswitch Participants Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.issuerParticipantsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.configWriter">Logs Configuration Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.configWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.instanceUser">Looker Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.proManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementEditor">Mandiant Attack Surface Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.attackSurfaceManagementEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementViewer">Mandiant Attack Surface Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.attackSurfaceManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringEditor">Mandiant Digital Threat Monitoring Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.digitalThreatMonitoringEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringViewer">Mandiant Digital Threat Monitoring Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.digitalThreatMonitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandEditor">Mandiant Expertise On Demand Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.expertiseOnDemandEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandViewer">Mandiant Expertise On Demand Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.expertiseOnDemandViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelEditor">Mandiant Threat Intel Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.threatIntelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelViewer">Mandiant Threat Intel Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.threatIntelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationEditor">Mandiant Validation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.validationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationViewer">Mandiant Validation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.validationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesAdmin">Monitoring Metrics Scopes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.metricsScopesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesViewer">Monitoring Metrics Scopes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.metricsScopesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer">Google Home Developer Console Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.consumerNetworkAdmin">Service Automation Consumer Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.consumerNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.groupAdmin">Group Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.groupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubAdmin">Hub &amp; Spoke Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.hubAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubViewer">Hub &amp; Spoke Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.hubViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigAdmin">Multicloud Data Transfer Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigViewer">Multicloud Data Transfer Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationAdmin">Destination Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferDestinationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationViewer">Destination Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferDestinationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointAdmin">Regional Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.regionalEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointViewer">Regional Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.regionalEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceClassUser">Service Class User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceClassUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceProducerAdmin">Service Automation Service Producer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceProducerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.spokeAdmin">Spoke Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.spokeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportAdmin">Transport Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.transportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportViewer">Transport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.transportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorAdmin">DNS Threat Detector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.dnsThreatDetectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorViewer">DNS Threat Detector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.dnsThreatDetectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.firewallEndpointAdmin">Firewall Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.firewallEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentAdmin">Intercept Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentViewer">Intercept Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointAdmin">Intercept Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointViewer">Intercept Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentAdmin">Mirroring Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentViewer">Mirroring Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointAdmin">Mirroring Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointViewer">Mirroring Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.securityProfileAdmin">Security Profile Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.securityProfileAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.inventoryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsViewer">Project Feature Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.vulnerabilityReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.productViewer">Payments Reseller Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.productViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.promotionViewer">Payments Reseller Promotions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.promotionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionViewer">Payments Reseller Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentViewer">Beacon Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.externalAccountKeyCreator">External Account Key Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  publicca.externalAccountKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbAdmin">AlloyDB Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.alloydbAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbViewer">AlloyDB Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.alloydbViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostAdmin">App Engine Version Cost Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.appengineversioncostAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostViewer">App Engine Version Cost Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.appengineversioncostViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsAdmin">BigQuery Slot Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectAdmin">BigQuery Recommender Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectViewer">BigQuery Recommender Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsViewer">BigQuery Slot Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewAdmin">BigQuery Materialized View Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryMaterializedViewAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewViewer">BigQuery Materialized View Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryMaterializedViewViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterAdmin">BigQuery Partitioning Clustering Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryPartitionClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterViewer">BigQuery Partitioning Clustering Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryPartitionClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceAdmin">Bigtable Cluster Performance Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigtableClusterPerformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceViewer">Bigtable Cluster Performance Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigtableClusterPerformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsAdmin">Cloud Asset Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudAssetInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsViewer">Cloud Asset Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudAssetInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationAdmin">Cloud Cost General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudCostRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationViewer">Cloud Cost General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudCostRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationAdmin">Cloud Deprecation General Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudDeprecationRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationViewer">Cloud Deprecation General Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudDeprecationRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationAdmin">Cloud Manageability General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudManageabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationViewer">Cloud Manageability General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudManageabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationAdmin">Cloud Performance General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudPerformanceRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationViewer">Cloud Performance General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudPerformanceRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationAdmin">Cloud Reliability General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudReliabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationViewer">Cloud Reliability General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudReliabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationAdmin">Cloud Security General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudSecurityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationViewer">Cloud Security General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudSecurityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlAdmin">Cloud SQL Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudsqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlViewer">Cloud SQL Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudsqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeAdmin">Compute Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.computeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeViewer">Compute Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.computeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisAdmin">GKE Diagnosis Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.containerDiagnosisAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisViewer">GKE Diagnosis Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.containerDiagnosisViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsAdmin">Dataflow Diagnostics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.dataflowDiagnosticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsViewer">Dataflow Diagnostics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.dataflowDiagnosticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingAdmin">Error Reporting Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.errorReportingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingViewer">Error Reporting Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.errorReportingViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesAdmin">Firestore Database Firebase rules Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasefirebaserulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesViewer">Firestore Database Firebase rules Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasefirebaserulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityAdmin">Firestore Database Reliability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityViewer">Firestore Database Reliability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallAdmin">Firewall Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firewallAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallViewer">Firewall Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firewallViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpAdmin">Google Maps Platform Insights/Recommendations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.gmpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpViewer">Google Maps Platform Insights/Recommendations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.gmpViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamViewer">IAM Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskAdmin">IAM Policy Change Risk Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iampolicychangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskViewer">IAM Policy Change Risk Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iampolicychangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityAdmin">Memorystore Manageability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoremanageabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityViewer">Memorystore Manageability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoremanageabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceAdmin">Memorystore Performance Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoreperformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceViewer">Memorystore Performance Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoreperformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityAdmin">Memorystore Reliability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystorereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityViewer">Memorystore Reliability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystorereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerAdmin">Network Analyzer Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlAdmin">Network Analyzer Cloud SQL Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerCloudSqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlViewer">Network Analyzer Cloud SQL Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerCloudSqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteAdmin">Network Analyzer Dynamic Route Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerDynamicRouteAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteViewer">Network Analyzer Dynamic Route Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerDynamicRouteViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityAdmin">Network Analyzer GKE Connectivity Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityViewer">Network Analyzer GKE Connectivity Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressAdmin">Network Analyzer GKE IP Address Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressViewer">Network Analyzer GKE IP Address Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountAdmin">Network Analyzer GKE Service Account Insights Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeServiceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountViewer">Network Analyzer GKE Service Account Insights Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeServiceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressAdmin">Network Analyzer IP Address Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressViewer">Network Analyzer IP Address Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerAdmin">Network Analyzer Load Balancer Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerLoadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerViewer">Network Analyzer Load Balancer Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerLoadBalancerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerViewer">Network Analyzer Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityAdmin">Network Analyzer VPC Connectivity Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerVpcConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityViewer">Network Analyzer VPC Connectivity Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerVpcConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyAdmin">Org Policy Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyViewer">Org Policy Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.orgPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionAdmin">Product Suggestion Recommenders Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.productSuggestionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionViewer">Product Suggestion Recommenders Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.productSuggestionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudAdmin">Project Usage Commitment Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudViewer">Project Usage Commitment Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilAdmin">Project Utilization Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectUtilAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilViewer">Project Utilization Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectUtilViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentChangeConfigAdmin">RecentChange RecommenderConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.recentChangeConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskAdmin">Recent Change Risk Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.recentchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskViewer">Recent Change Risk Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.recentchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitAdmin">Service Limit Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceLimitAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitViewer">Service Limit Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceLimitViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskAdmin">Service Account Change Risk Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceaccntchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskViewer">Service Account Change Risk Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceaccntchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerAdmin">Spanner Project Reliability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.spannerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerViewer">Spanner Project Reliability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.spannerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionViewer">Roads Selection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionAdder">Secret Manager Secret Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator">Overwatch Activator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchActivator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoCreator">Secure Source Manager Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoPullRequestApprover">Secure Source Manager Repository Pull Request Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoPullRequestApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.networkAttacher">Service Directory Network Attacher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.networkAttacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.pscAuthorizedService">Private Service Connect Authorized Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.pscAuthorizedService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.viewer">Stackdriver Accounts Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.accounts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.insightsCollectorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentBuilder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.developer">Subscribe with Google Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  subscribewithgoogledeveloper.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.serviceAgent">Bare Metal Solution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection#containerthreatdetection.serviceAgent">Container Threat Detection Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerthreatdetection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkedataplanemanagement#gkedataplanemanagement.warpRunServiceAgent">Warp Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkedataplanemanagement.warpRunServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsControlPlaneServiceAgent">KubeRun Events Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kuberun.eventsControlPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsDataPlaneServiceAgent">KubeRun Events Data Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kuberun.eventsDataPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.restrictedServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.serviceAgent">Looker Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.serviceAgent">Parallelstore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.attackSurfaceManagementScannerServiceAgent">Attack Surface Management Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.attackSurfaceManagementScannerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spectrumsas.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.getIamPolicy" class="permission-name add-link" data-text="resourcemanager.projects.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.developerAdmin">Apigee Developer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.developerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.environmentAdmin">Apigee Environment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.environmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.crossProjectServiceAgent">GKE Hub Cross Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.crossProjectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.list" class="permission-name add-link" data-text="resourcemanager.projects.list" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.projects.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.admin">Agent Platform Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.editor">Aiplatform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user">Agent Platform User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.viewer">Agent Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.admin">Androidmanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  androidmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.viewer">Apigee Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.viewer">Apigeeconnect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.admin">Cloud Apigee Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.editor">Cloud Apigee Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.viewer">Cloud Apigee Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer">Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor">Assured OSS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer">Assured OSS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  axt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin">Batch Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer">Batch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.admin">Cloud BeyondCorp Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.editor">Cloud BeyondCorp Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.viewer">Cloud BeyondCorp Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  beyondcorp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.metadataViewer">BigQuery Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.readSessionUser">BigQuery Read Session User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.readSessionUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceAdmin">BigQuery Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.resourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceEditor">BigQuery Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.resourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceViewer">BigQuery Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.resourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatapolicy#bigquerydatapolicy.editor">BigQuery Data Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatapolicy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.admin">Carestudio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.viewer">Care Studio Patients Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin">Chat Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.viewer">Chat Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.editor">Chronicle API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.viewer">Chronicle API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin">Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer">Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.admin">Gemini for Google Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.editor">Gemini for Google Cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.user">Gemini for Google Cloud User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.viewer">Gemini for Google Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.admin">Cloud Build Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.editor">Cloud Build Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.viewer">Cloud Build Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.admin">Cloudprivatecatalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.viewer">Cloudprivatecatalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.viewer">Cloud Profiler Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.viewer">Cloud Quotas Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudquotas.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.admin">Commerce Organization Governance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.viewer">Commerce Organization Governance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.admin">Commerce Producer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.viewer">Commerce Producer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer">Confidentialcomputing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  confidentialcomputing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterViewer">Kubernetes Engine Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.clusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.developer">Kubernetes Engine Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.editor">Kubernetes Engine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.viewer">Kubernetes Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.admin">Database Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasecenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.viewer">Database Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasecenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.editor">Databasesconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.viewer">Databasesconsole Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.admin">Data pipelines Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.viewer">Data pipelines Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.viewer">Dataproc Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.admin">Dataproc Resource Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocrm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.viewer">Dataproc Resource Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocrm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.editor">Discovery Engine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.viewer">Discovery Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.admin">Earth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.viewer">Earth Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.admin">Enterprise Purchasing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterprisepurchasing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.editor">Enterprise Purchasing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterprisepurchasing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.viewer">Enterprise Purchasing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterprisepurchasing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.admin">Eventarc Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.editor">Eventarc Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.viewer">Eventarc Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.admin">Firebase App Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.viewer">Firebase App Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.admin">Firebase Data Connect API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.viewer">Firebase Data Connect API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.admin">Firebase Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.viewer">Firebase Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.viewer">Cloud Storage for Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.admin">Firebase AI Logic Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasevertexai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.viewer">Firebase AI Logic Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasevertexai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.viewer">Kubernetesmetadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer">Cloud Life Sciences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.admin">Logging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.admin">Google Cloud Managed Lustre Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lustre.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.viewer">Google Cloud Managed Lustre Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lustre.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.admin">MCP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mcp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser">MCP Tool User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mcp.toolUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.viewer">Memorystore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memorystore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer">Nestconsole Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.editor">Network Connectivity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.admin">Networksecurity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.editor">Networksecurity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.viewer">Networksecurity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.admin">Network Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.editor">Network Services Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.viewer">Network Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ondemandscanning#ondemandscanning.viewer">On-Demand Scanning Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ondemandscanning.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.admin">Opsconfigmonitoring Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  opsconfigmonitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.viewer">Opsconfigmonitoring Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  opsconfigmonitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.admin">Publicca Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  publicca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer">Subscription Linking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.admin">Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.editor">Recommender Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.editor">Cloud Memorystore Redis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.viewer">Cloud Memorystore Redis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer">Route Optimization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig#saasconfig.viewer">SaaS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretAccessor">Secret Manager Secret Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.admin">Servicehealth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicehealth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.viewer">Personalized Service Health Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicehealth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.viewer">Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.viewer">Stackdriver Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.admin">Storage Batch Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagebatchoperations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.viewer">Storage Batch Operations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagebatchoperations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.admin">Subscribewithgoogledeveloper Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  subscribewithgoogledeveloper.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.viewer">Subscribewithgoogledeveloper Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  subscribewithgoogledeveloper.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.editor">Telemetry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telemetry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.admin">TPU Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  tpu.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.viewer">TPU Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  tpu.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.viewer">Trafficdirector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer">Translation Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin">Visual Inspection AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.entityTypeOwner">Agent Platform Feature Store EntityType owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.entityTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreAdmin">Agent Platform Feature Store Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataViewer">Agent Platform Feature Store Data Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataWriter">Agent Platform Feature Store Data Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreResourceViewer">Agent Platform Feature Store Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreResourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreUser">Agent Platform Feature Store User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.featurestoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsEditor">Apigee Analytics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.analyticsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsViewer">Apigee Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.developerAdmin">Apigee Developer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.developerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.environmentAdmin">Apigee Environment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.environmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.monetizationAdmin">Apigee Monetization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.monetizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.portalAdmin">Apigee Portal Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.portalAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.spaceConsoleUser">Apigee Space Console User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.spaceConsoleUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.worker">Cloud Apigee Registry Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeregistry.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appCreator">App Engine Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver">Appliance troubleshooting commands approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.troubleshooter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.predictor">AutoML Predictor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.predictor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor">Batch Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer">Batch Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor">Batch ResourceAllowance Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.resourceAllowancesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer">Batch ResourceAllowance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.resourceAllowancesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.dataGovernor">Chronicle API Data Governor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.dataGovernor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationAdmin">Chronicle API Federation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.federationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationViewer">Chronicle API Federation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.federationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.limitedViewer">Chronicle API Limited Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.limitedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.restrictedDataAccessViewer">Chronicle API Restricted Data Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.restrictedDataAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarRemoteAgent">Chronicle SOAR Remote Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarRemoteAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesAdmin">Code Repository Indexes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeRepositoryIndexesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesViewer">Code Repository Indexes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeRepositoryIndexesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.approver">Cloud Build Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.editor">Cloud Build Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.viewer">Cloud Build Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionAdmin">Cloud Build Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.connectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionViewer">Cloud Build Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.connectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsEditor">Cloud Build Integrations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.integrationsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsOwner">Cloud Build Integrations Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.integrationsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsViewer">Cloud Build Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.integrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolEditor">Cloud Build WorkerPool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.workerPoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolOwner">Cloud Build WorkerPool Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.workerPoolOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolViewer">Cloud Build WorkerPool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.workerPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.consumer">Catalog Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalog.consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportEditor">Advisory Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.advisorySupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportViewer">Advisory Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.advisorySupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.enqueuer">Cloud Tasks Enqueuer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.enqueuer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskDeleter">Cloud Tasks Task Deleter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskRunner">Cloud Tasks Task Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigViewer">Commerce Business Enablement PaymentConfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.user">Governed Marketplace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer">Commerce Price Management Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.publicIpAdmin">Compute Public IP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.publicIpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyAdmin">Compute VM extension policy admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.vmExtensionPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyViewer">Compute VM extension policy viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.vmExtensionPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.viewer">Container Analysis Notes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.viewer">Container Analysis Occurrences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryAdmin">Studio Query Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.studioQueryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryUser">Studio Query User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databasesconsole.studioQueryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.invoker">Data pipelines Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessViewer">Dataproc Serverless Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serverlessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceEditor">Gemini Enterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceRestrictedUser">Gemini Enterprise Restricted User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceRestrictedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceViewer">Gemini Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmOwner">Cloud NotebookLM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.notebookLmOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmUser">Cloud NotebookLM User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.notebookLmUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsAdmin">Earth Subscriptions Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsViewer">Earth Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earth.subscriptionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.offlineCredentialUser">Edge Container Cluster offline Credential User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.offlineCredentialUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.connectionPublisher">Eventarc Connection Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.connectionPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.developer">Eventarc Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.publisher">Eventarc Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.developer">Firebase App Hosting Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.certificateViewer">Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.certificateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.issuerParticipantsAdmin">Issuerswitch Participants Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.issuerParticipantsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.configWriter">Logs Configuration Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.configWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.instanceUser">Looker Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.proManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementEditor">Mandiant Attack Surface Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.attackSurfaceManagementEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementViewer">Mandiant Attack Surface Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.attackSurfaceManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringEditor">Mandiant Digital Threat Monitoring Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.digitalThreatMonitoringEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringViewer">Mandiant Digital Threat Monitoring Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.digitalThreatMonitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandEditor">Mandiant Expertise On Demand Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.expertiseOnDemandEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandViewer">Mandiant Expertise On Demand Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.expertiseOnDemandViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelEditor">Mandiant Threat Intel Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.threatIntelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelViewer">Mandiant Threat Intel Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.threatIntelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationEditor">Mandiant Validation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.validationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationViewer">Mandiant Validation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mandiant.validationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesAdmin">Monitoring Metrics Scopes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.metricsScopesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesViewer">Monitoring Metrics Scopes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.metricsScopesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer">Google Home Developer Console Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.consumerNetworkAdmin">Service Automation Consumer Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.consumerNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.groupAdmin">Group Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.groupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubAdmin">Hub &amp; Spoke Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.hubAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubViewer">Hub &amp; Spoke Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.hubViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigAdmin">Multicloud Data Transfer Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigViewer">Multicloud Data Transfer Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationAdmin">Destination Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferDestinationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationViewer">Destination Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.multicloudDataTransferDestinationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointAdmin">Regional Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.regionalEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointViewer">Regional Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.regionalEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceClassUser">Service Class User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceClassUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceProducerAdmin">Service Automation Service Producer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceProducerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.spokeAdmin">Spoke Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.spokeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportAdmin">Transport Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.transportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportViewer">Transport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.transportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorAdmin">DNS Threat Detector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.dnsThreatDetectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorViewer">DNS Threat Detector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.dnsThreatDetectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.firewallEndpointAdmin">Firewall Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.firewallEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentAdmin">Intercept Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentViewer">Intercept Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointAdmin">Intercept Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointViewer">Intercept Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.interceptEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentAdmin">Mirroring Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentViewer">Mirroring Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointAdmin">Mirroring Endpoint Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointViewer">Mirroring Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.mirroringEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.securityProfileAdmin">Security Profile Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networksecurity.securityProfileAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.guestPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.inventoryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.patchJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsViewer">Project Feature Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.projectFeatureSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.vulnerabilityReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.productViewer">Payments Reseller Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.productViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.promotionViewer">Payments Reseller Promotions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.promotionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionViewer">Payments Reseller Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentViewer">Beacon Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.externalAccountKeyCreator">External Account Key Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  publicca.externalAccountKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbAdmin">AlloyDB Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.alloydbAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbViewer">AlloyDB Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.alloydbViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostAdmin">App Engine Version Cost Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.appengineversioncostAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostViewer">App Engine Version Cost Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.appengineversioncostViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsAdmin">BigQuery Slot Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectAdmin">BigQuery Recommender Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectViewer">BigQuery Recommender Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsViewer">BigQuery Slot Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewAdmin">BigQuery Materialized View Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryMaterializedViewAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewViewer">BigQuery Materialized View Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryMaterializedViewViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterAdmin">BigQuery Partitioning Clustering Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryPartitionClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterViewer">BigQuery Partitioning Clustering Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigqueryPartitionClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceAdmin">Bigtable Cluster Performance Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigtableClusterPerformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceViewer">Bigtable Cluster Performance Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigtableClusterPerformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsAdmin">Cloud Asset Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudAssetInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsViewer">Cloud Asset Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudAssetInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationAdmin">Cloud Cost General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudCostRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationViewer">Cloud Cost General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudCostRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationAdmin">Cloud Deprecation General Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudDeprecationRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationViewer">Cloud Deprecation General Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudDeprecationRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationAdmin">Cloud Manageability General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudManageabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationViewer">Cloud Manageability General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudManageabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationAdmin">Cloud Performance General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudPerformanceRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationViewer">Cloud Performance General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudPerformanceRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationAdmin">Cloud Reliability General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudReliabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationViewer">Cloud Reliability General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudReliabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationAdmin">Cloud Security General Recommendations Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudSecurityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationViewer">Cloud Security General Recommendations Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudSecurityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlAdmin">Cloud SQL Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudsqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlViewer">Cloud SQL Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.cloudsqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeAdmin">Compute Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.computeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeViewer">Compute Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.computeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisAdmin">GKE Diagnosis Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.containerDiagnosisAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisViewer">GKE Diagnosis Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.containerDiagnosisViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsAdmin">Dataflow Diagnostics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.dataflowDiagnosticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsViewer">Dataflow Diagnostics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.dataflowDiagnosticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingAdmin">Error Reporting Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.errorReportingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingViewer">Error Reporting Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.errorReportingViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesAdmin">Firestore Database Firebase rules Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasefirebaserulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesViewer">Firestore Database Firebase rules Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasefirebaserulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityAdmin">Firestore Database Reliability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityViewer">Firestore Database Reliability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firestoredatabasereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallAdmin">Firewall Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firewallAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallViewer">Firewall Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.firewallViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpAdmin">Google Maps Platform Insights/Recommendations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.gmpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpViewer">Google Maps Platform Insights/Recommendations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.gmpViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamViewer">IAM Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskAdmin">IAM Policy Change Risk Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iampolicychangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskViewer">IAM Policy Change Risk Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iampolicychangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityAdmin">Memorystore Manageability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoremanageabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityViewer">Memorystore Manageability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoremanageabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceAdmin">Memorystore Performance Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoreperformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceViewer">Memorystore Performance Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystoreperformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityAdmin">Memorystore Reliability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystorereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityViewer">Memorystore Reliability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.memorystorereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerAdmin">Network Analyzer Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlAdmin">Network Analyzer Cloud SQL Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerCloudSqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlViewer">Network Analyzer Cloud SQL Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerCloudSqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteAdmin">Network Analyzer Dynamic Route Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerDynamicRouteAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteViewer">Network Analyzer Dynamic Route Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerDynamicRouteViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityAdmin">Network Analyzer GKE Connectivity Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityViewer">Network Analyzer GKE Connectivity Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressAdmin">Network Analyzer GKE IP Address Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressViewer">Network Analyzer GKE IP Address Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountAdmin">Network Analyzer GKE Service Account Insights Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeServiceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountViewer">Network Analyzer GKE Service Account Insights Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerGkeServiceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressAdmin">Network Analyzer IP Address Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressViewer">Network Analyzer IP Address Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerAdmin">Network Analyzer Load Balancer Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerLoadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerViewer">Network Analyzer Load Balancer Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerLoadBalancerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerViewer">Network Analyzer Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityAdmin">Network Analyzer VPC Connectivity Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerVpcConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityViewer">Network Analyzer VPC Connectivity Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.networkAnalyzerVpcConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyAdmin">Org Policy Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyViewer">Org Policy Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.orgPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionAdmin">Product Suggestion Recommenders Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.productSuggestionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionViewer">Product Suggestion Recommenders Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.productSuggestionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudAdmin">Project Usage Commitment Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudViewer">Project Usage Commitment Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilAdmin">Project Utilization Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectUtilAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilViewer">Project Utilization Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.projectUtilViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentChangeConfigAdmin">RecentChange RecommenderConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.recentChangeConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskAdmin">Recent Change Risk Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.recentchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskViewer">Recent Change Risk Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.recentchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitAdmin">Service Limit Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceLimitAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitViewer">Service Limit Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceLimitViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskAdmin">Service Account Change Risk Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceaccntchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskViewer">Service Account Change Risk Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.serviceaccntchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerAdmin">Spanner Project Reliability Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.spannerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerViewer">Spanner Project Reliability Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.spannerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionViewer">Roads Selection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionAdder">Secret Manager Secret Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator">Overwatch Activator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchActivator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoCreator">Secure Source Manager Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoPullRequestApprover">Secure Source Manager Repository Pull Request Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoPullRequestApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.networkAttacher">Service Directory Network Attacher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.networkAttacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.pscAuthorizedService">Private Service Connect Authorized Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.pscAuthorizedService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.viewer">Stackdriver Accounts Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stackdriver.accounts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.insightsCollectorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentBuilder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.developer">Subscribe with Google Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  subscribewithgoogledeveloper.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  videostitcher.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection#containerthreatdetection.serviceAgent">Container Threat Detection Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerthreatdetection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkedataplanemanagement#gkedataplanemanagement.warpRunServiceAgent">Warp Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkedataplanemanagement.warpRunServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.serviceAgent">Parallelstore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.move" class="permission-name add-link" data-text="resourcemanager.projects.move" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.projects.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectMover">Project Mover</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderMover">Folder Mover</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderMover</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.searchPolicyBindings" class="permission-name add-link" data-text="resourcemanager.projects.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.setIamPolicy" class="permission-name add-link" data-text="resourcemanager.projects.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.crossProjectServiceAgent">GKE Hub Cross Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.crossProjectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.undelete" class="permission-name add-link" data-text="resourcemanager.projects.undelete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.update" class="permission-name add-link" data-text="resourcemanager.projects.update" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectMover">Project Mover</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.projects.updateLiens" class="permission-name add-link" data-text="resourcemanager.projects.updateLiens" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.proManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.lienModifier">Project Lien Modifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.lienModifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.projects.updatePolicyBinding" class="permission-name add-link" data-text="resourcemanager.projects.updatePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  projects.  updatePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagHolds.create" class="permission-name add-link" data-text="resourcemanager.tagHolds.create" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagHolds.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagHoldAdmin">Tag Hold Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagHoldAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagHolds.delete" class="permission-name add-link" data-text="resourcemanager.tagHolds.delete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagHolds.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagHoldAdmin">Tag Hold Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagHoldAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagHolds.list" class="permission-name add-link" data-text="resourcemanager.tagHolds.list" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagHoldAdmin">Tag Hold Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagHoldAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagKeys.create" class="permission-name add-link" data-text="resourcemanager.tagKeys.create" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagKeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagKeys.delete" class="permission-name add-link" data-text="resourcemanager.tagKeys.delete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagKeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagKeys.get" class="permission-name add-link" data-text="resourcemanager.tagKeys.get" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagKeys.getIamPolicy" class="permission-name add-link" data-text="resourcemanager.tagKeys.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagKeys.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagKeys.list" class="permission-name add-link" data-text="resourcemanager.tagKeys.list" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagKeys.setIamPolicy" class="permission-name add-link" data-text="resourcemanager.tagKeys.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagKeys.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagKeys.update" class="permission-name add-link" data-text="resourcemanager.tagKeys.update" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagKeys.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagValueBindings.create" class="permission-name add-link" data-text="resourcemanager.tagValueBindings.create" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagValueBindings.delete" class="permission-name add-link" data-text="resourcemanager.tagValueBindings.delete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagValues.create" class="permission-name add-link" data-text="resourcemanager.tagValues.create" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValues.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagValues.delete" class="permission-name add-link" data-text="resourcemanager.tagValues.delete" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValues.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagValues.get" class="permission-name add-link" data-text="resourcemanager.tagValues.get" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsViewer">Security Center Resource Value Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagValues.getIamPolicy" class="permission-name add-link" data-text="resourcemanager.tagValues.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValues.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagValues.list" class="permission-name add-link" data-text="resourcemanager.tagValues.list" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcemanager.tagValues.setIamPolicy" class="permission-name add-link" data-text="resourcemanager.tagValues.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValues.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcemanager.tagValues.update" class="permission-name add-link" data-text="resourcemanager.tagValues.update" tabindex="-1"><code dir="ltr" translate="no">resourcemanager.  tagValues.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
