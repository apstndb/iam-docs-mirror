---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/managedidentities
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities
title: Managed Service for Microsoft Active Directory roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Managed Service for Microsoft Active Directory. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Managed Service for Microsoft Active Directory roles

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
<td><h4 id="managedidentities.admin" class="role-title add-link" data-text="Google Cloud Managed Identities Admin" tabindex="-1">Google Cloud Managed Identities Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p>Full access to Google Cloud Managed Identities Domains and related resources. Intended to be granted on a project-level.</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  backups.  create</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.backups.get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.backups.list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  update</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  attachTrust</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  checkMigrationPermission</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  create</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  detachTrust</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  disableMigration</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  domainJoinMachine</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  enableMigration</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  extendSchema</code></li>
<li><code dir="ltr" translate="no">managedidentities.domains.get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.domains.list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  reconfigureTrust</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  resetpassword</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  restore</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  update</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  updateLDAPSSettings</code></li>
<li><code dir="ltr" translate="no">managedidentities.  domains.  validateTrust</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  create</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.peerings.get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  update</code></li>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.editor" class="role-title add-link" data-text="Google Cloud Managed Identities Editor" tabindex="-1">Google Cloud Managed Identities Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p>Editor role for Google Cloud Managed Identities</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.  backups.  create</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  delete</code></p>
<p><code dir="ltr" translate="no">managedidentities.backups.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.backups.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  update</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  attachTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  checkMigrationPermission</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  create</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  delete</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  detachTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  disableMigration</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  domainJoinMachine</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  enableMigration</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  extendSchema</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  reconfigureTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  resetpassword</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  restore</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  update</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  updateLDAPSSettings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  validateTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  create</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  delete</code></p>
<p><code dir="ltr" translate="no">managedidentities.peerings.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  update</code></p>
<p><code dir="ltr" translate="no">managedidentities.  sqlintegrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.viewer" class="role-title add-link" data-text="Google Cloud Managed Identities Viewer" tabindex="-1">Google Cloud Managed Identities Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p>Read-only access to Google Cloud Managed Identities Domains and related resources.</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.backups.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.backups.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.  operations.  get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  operations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.peerings.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  sqlintegrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.backupAdmin" class="role-title add-link" data-text="Google Cloud Managed Identities Backup Admin" tabindex="-1">Google Cloud Managed Identities Backup Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p>Full access to Google Cloud Managed Identities Backup and related resources. Intended to be granted on a project-level</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.backups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  backups.  create</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.backups.get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.backups.list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.domains.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.backupViewer" class="role-title add-link" data-text="Google Cloud Managed Identities Backup Viewer" tabindex="-1">Google Cloud Managed Identities Backup Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p>Read-only access to Google Cloud Managed Identities Backup and related resources.</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.backups.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.backups.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.  operations.  get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  operations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domainAdmin" class="role-title add-link" data-text="Google Cloud Managed Identities Domain Admin" tabindex="-1">Google Cloud Managed Identities Domain Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p>Read-Update-Delete to Google Cloud Managed Identities Domains and related resources. Intended to be granted on a resource (domain) level.</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.backups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  backups.  create</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.backups.get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.backups.list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  backups.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.  domains.  attachTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  checkMigrationPermission</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  delete</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  detachTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  disableMigration</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  domainJoinMachine</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  enableMigration</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  extendSchema</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  reconfigureTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  resetpassword</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  restore</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  update</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  updateLDAPSSettings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  validateTrust</code></p>
<p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.  operations.  get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  operations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  sqlintegrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domainJoin" class="role-title add-link" data-text="Google Cloud Managed Identities Domain Join Beta" tabindex="-1">Google Cloud Managed Identities Domain Join <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.domainJoin</code> )</p>
<p>Access to domain join VMs with Cloud AD</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.  domains.  domainJoinMachine</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.peeringAdmin" class="role-title add-link" data-text="Google Cloud Managed Identities Peering Admin" tabindex="-1">Google Cloud Managed Identities Peering Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p>Full access to Google Cloud Managed Identities Domains and related resources. Intended to be granted on a project-level</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.peerings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  create</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  delete</code></li>
<li><code dir="ltr" translate="no">managedidentities.peerings.get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">managedidentities.  peerings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.peeringViewer" class="role-title add-link" data-text="Google Cloud Managed Identities Peering Viewer" tabindex="-1">Google Cloud Managed Identities Peering Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p>
<p>Read-only access to Google Cloud Managed Identities Peering and related resources.</p></td>
<td><p><code dir="ltr" translate="no">managedidentities.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedidentities.  locations.  get</code></li>
<li><code dir="ltr" translate="no">managedidentities.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedidentities.  operations.  get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  operations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.peerings.get</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></p>
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
<td><h4 id="managedidentities.serviceAgent" class="role-title add-link" data-text="Cloud Managed Identities Service Agent" tabindex="-1">Cloud Managed Identities Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  managedidentities.serviceAgent</code> )</p>
<p>Gives Managed Identities service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">dns.changes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.changes.create</code></li>
<li><code dir="ltr" translate="no">dns.changes.get</code></li>
<li><code dir="ltr" translate="no">dns.changes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.dnsKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.dnsKeys.get</code></li>
<li><code dir="ltr" translate="no">dns.dnsKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZoneOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.managedZoneOperations.get</code></li>
<li><code dir="ltr" translate="no">dns.managedZoneOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.update</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSPolicy</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.policies.create</code></p>
<p><code dir="ltr" translate="no">dns.policies.delete</code></p>
<p><code dir="ltr" translate="no">dns.policies.get</code></p>
<p><code dir="ltr" translate="no">dns.policies.list</code></p>
<p><code dir="ltr" translate="no">dns.policies.update</code></p>
<p><code dir="ltr" translate="no">dns.projects.get</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.get</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.responsePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.responsePolicies.create</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.delete</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.get</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.list</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.responsePolicyRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.create</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.delete</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.get</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.list</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Managed Service for Microsoft Active Directory permissions

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
<td><h4 id="managedidentities.backups.create" class="permission-name add-link" data-text="managedidentities.backups.create" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  backups.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.backups.delete" class="permission-name add-link" data-text="managedidentities.backups.delete" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  backups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.backups.get" class="permission-name add-link" data-text="managedidentities.backups.get" tabindex="-1"><code dir="ltr" translate="no">managedidentities.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.backups.getIamPolicy" class="permission-name add-link" data-text="managedidentities.backups.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.backups.list" class="permission-name add-link" data-text="managedidentities.backups.list" tabindex="-1"><code dir="ltr" translate="no">managedidentities.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.backups.setIamPolicy" class="permission-name add-link" data-text="managedidentities.backups.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  backups.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.backups.update" class="permission-name add-link" data-text="managedidentities.backups.update" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  backups.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.attachTrust" class="permission-name add-link" data-text="managedidentities.domains.attachTrust" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  attachTrust</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.checkMigrationPermission" class="permission-name add-link" data-text="managedidentities.domains.checkMigrationPermission" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  checkMigrationPermission</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.create" class="permission-name add-link" data-text="managedidentities.domains.create" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.createTagBinding" class="permission-name add-link" data-text="managedidentities.domains.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.delete" class="permission-name add-link" data-text="managedidentities.domains.delete" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.deleteTagBinding" class="permission-name add-link" data-text="managedidentities.domains.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.detachTrust" class="permission-name add-link" data-text="managedidentities.domains.detachTrust" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  detachTrust</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.disableMigration" class="permission-name add-link" data-text="managedidentities.domains.disableMigration" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  disableMigration</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.domainJoinMachine" class="permission-name add-link" data-text="managedidentities.domains.domainJoinMachine" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  domainJoinMachine</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainJoin">Google Cloud Managed Identities Domain Join</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainJoin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.enableMigration" class="permission-name add-link" data-text="managedidentities.domains.enableMigration" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  enableMigration</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.extendSchema" class="permission-name add-link" data-text="managedidentities.domains.extendSchema" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  extendSchema</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.get" class="permission-name add-link" data-text="managedidentities.domains.get" tabindex="-1"><code dir="ltr" translate="no">managedidentities.domains.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainJoin">Google Cloud Managed Identities Domain Join</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainJoin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.getIamPolicy" class="permission-name add-link" data-text="managedidentities.domains.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.list" class="permission-name add-link" data-text="managedidentities.domains.list" tabindex="-1"><code dir="ltr" translate="no">managedidentities.domains.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.listEffectiveTags" class="permission-name add-link" data-text="managedidentities.domains.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.listTagBindings" class="permission-name add-link" data-text="managedidentities.domains.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.reconfigureTrust" class="permission-name add-link" data-text="managedidentities.domains.reconfigureTrust" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  reconfigureTrust</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.resetpassword" class="permission-name add-link" data-text="managedidentities.domains.resetpassword" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  resetpassword</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.restore" class="permission-name add-link" data-text="managedidentities.domains.restore" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.setIamPolicy" class="permission-name add-link" data-text="managedidentities.domains.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.update" class="permission-name add-link" data-text="managedidentities.domains.update" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.domains.updateLDAPSSettings" class="permission-name add-link" data-text="managedidentities.domains.updateLDAPSSettings" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  updateLDAPSSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.domains.validateTrust" class="permission-name add-link" data-text="managedidentities.domains.validateTrust" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  domains.  validateTrust</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.locations.get" class="permission-name add-link" data-text="managedidentities.locations.get" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.locations.list" class="permission-name add-link" data-text="managedidentities.locations.list" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.operations.cancel" class="permission-name add-link" data-text="managedidentities.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.operations.delete" class="permission-name add-link" data-text="managedidentities.operations.delete" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.operations.get" class="permission-name add-link" data-text="managedidentities.operations.get" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.operations.list" class="permission-name add-link" data-text="managedidentities.operations.list" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.peerings.create" class="permission-name add-link" data-text="managedidentities.peerings.create" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  peerings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.peerings.delete" class="permission-name add-link" data-text="managedidentities.peerings.delete" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  peerings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.peerings.get" class="permission-name add-link" data-text="managedidentities.peerings.get" tabindex="-1"><code dir="ltr" translate="no">managedidentities.peerings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.peerings.getIamPolicy" class="permission-name add-link" data-text="managedidentities.peerings.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.peerings.list" class="permission-name add-link" data-text="managedidentities.peerings.list" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.peerings.setIamPolicy" class="permission-name add-link" data-text="managedidentities.peerings.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  peerings.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.peerings.update" class="permission-name add-link" data-text="managedidentities.peerings.update" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  peerings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.peeringAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedidentities.sqlintegrations.get" class="permission-name add-link" data-text="managedidentities.sqlintegrations.get" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedidentities.sqlintegrations.list" class="permission-name add-link" data-text="managedidentities.sqlintegrations.list" tabindex="-1"><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedidentities.domainAdmin</code> )</p></td>
</tr>
</tbody>
</table>
