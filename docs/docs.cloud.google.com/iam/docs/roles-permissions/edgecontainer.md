---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer
title: Distributed Cloud Edge Container roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Distributed Cloud Edge Container. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Distributed Cloud Edge Container roles

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
<td><h4 id="edgecontainer.admin" class="role-title add-link" data-text="Edge Container Admin" tabindex="-1">Edge Container Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p>Full access to Edge Container all resources.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.clusters.create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.clusters.delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  clusters.  generateAccessToken</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  clusters.  generateOfflineCredential</code></li>
<li><code dir="ltr" translate="no">edgecontainer.clusters.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  clusters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.clusters.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  clusters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.clusters.update</code></li>
<li><code dir="ltr" translate="no">edgecontainer.clusters.upgrade</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.machines.create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.machines.delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.machines.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.machines.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  machines.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.machines.update</code></li>
<li><code dir="ltr" translate="no">edgecontainer.machines.use</code></li>
<li><code dir="ltr" translate="no">edgecontainer.nodePools.create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.nodePools.delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.nodePools.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  nodePools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.nodePools.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  nodePools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.nodePools.update</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.serverconfig.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  describekey</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  disablekey</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  generatekey</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  listkeys</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  update</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  disable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  enable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  disable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  enable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.zones.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zones.  getZoneIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgecontainer.zones.list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.zones.listRoles</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zones.  setZoneIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.editor" class="role-title add-link" data-text="Edgecontainer Editor" tabindex="-1">Edgecontainer Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p>Editor role for edgecontainer</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.apikeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.clusters.create</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.delete</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  generateAccessToken</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.update</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.upgrade</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  identityproviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.machines.create</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.delete</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.update</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.use</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.create</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.delete</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  nodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.update</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.serverconfig.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  describekey</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  disablekey</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  generatekey</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  listkeys</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  create</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  delete</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  update</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zonalProjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  disable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  enable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.zonalservices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  disable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  enable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.zones.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zones.  getZoneIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.listRoles</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.viewer" class="role-title add-link" data-text="Edge Container Viewer" tabindex="-1">Edge Container Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p>Read-only access to Edge Container all resources.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.apikeys.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  generateAccessToken</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  identityproviders.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.machines.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  nodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.serverconfig.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  describekey</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  generatekey</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  listkeys</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalservices.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zones.  getZoneIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.listRoles</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.apiKeyAdmin" class="role-title add-link" data-text="Edge Container API Key Admin" tabindex="-1">Edge Container API Key Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p>Access to manage API Keys.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.apikeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.apiKeyViewer" class="role-title add-link" data-text="Edge Container API Key Viewer" tabindex="-1">Edge Container API Key Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p>Read-only access to API Keys.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.apikeys.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.identityProviderAdmin" class="role-title add-link" data-text="Edge Container Identity Provider Admin" tabindex="-1">Edge Container Identity Provider Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p>
<p>Access to manage Identity Providers.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.  identityproviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  create</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.identityProviderViewer" class="role-title add-link" data-text="Edge Container Identity Provider Viewer" tabindex="-1">Edge Container Identity Provider Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.identityProviderViewer</code> )</p>
<p>Read-only access to Identity Providers.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.  identityproviders.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.machineUser" class="role-title add-link" data-text="Edge Container Machine User" tabindex="-1">Edge Container Machine User</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p>
<p>Access to use Edge Container Machine resources.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.machines.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.use</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.offlineCredentialUser" class="role-title add-link" data-text="Edge Container Cluster offline Credential User" tabindex="-1">Edge Container Cluster offline Credential User</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.offlineCredentialUser</code> )</p>
<p>Access to get Edge Container cluster offline credentials</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.  clusters.  generateOfflineCredential</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceAccountAdmin" class="role-title add-link" data-text="Edge Container Service Account Admin" tabindex="-1">Edge Container Service Account Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p>
<p>Access to manage Service Accounts.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  create</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  delete</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.serviceAccountKeyAdmin" class="role-title add-link" data-text="Edge Container Service Account Key Admin" tabindex="-1">Edge Container Service Account Key Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p>
<p>Access to manage Service Account Keys.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  describekey</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  disablekey</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  generatekey</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  listkeys</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceAccountKeyViewer" class="role-title add-link" data-text="Edge Container Service Account Key Viewer" tabindex="-1">Edge Container Service Account Key Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyViewer</code> )</p>
<p>Access to view Service Account Keys.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  describekey</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  listkeys</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.serviceAccountViewer" class="role-title add-link" data-text="Edge Container Service Account Viewer" tabindex="-1">Edge Container Service Account Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.serviceAccountViewer</code> )</p>
<p>Read-only access to Service Accounts.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zonalProjectAdmin" class="role-title add-link" data-text="Edge Container Zonal Project Admin" tabindex="-1">Edge Container Zonal Project Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p>Access to manage zonal projects.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.zonalProjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  disable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  enable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.zones.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zonalProjectViewer" class="role-title add-link" data-text="Edge Container Zonal Project Viewer" tabindex="-1">Edge Container Zonal Project Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p>Read-only access to zonal projects.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zonalServiceAdmin" class="role-title add-link" data-text="Edge Container Zonal Service Admin" tabindex="-1">Edge Container Zonal Service Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p>Access to mutate zonal service.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.zonalservices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  disable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  enable</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zonalServiceViewer" class="role-title add-link" data-text="Edge Container Zonal Service Viewer" tabindex="-1">Edge Container Zonal Service Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p>Read-only access to zonal services.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalservices.  get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zoneIamAdmin" class="role-title add-link" data-text="Edge Container Zone Iam Policy Admin" tabindex="-1">Edge Container Zone Iam Policy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zoneIamAdmin</code> )</p>
<p>Access to manage Iam Policy in the zone.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.  zones.  getZoneIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.listRoles</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zones.  setZoneIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zoneIamViewer" class="role-title add-link" data-text="Edge Container Zone Iam Policy Viewer" tabindex="-1">Edge Container Zone Iam Policy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zoneIamViewer</code> )</p>
<p>Read-only access to Iam Policy in the zone.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.  zones.  getZoneIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zoneRolesViewer" class="role-title add-link" data-text="Edge Container Roles Viewer" tabindex="-1">Edge Container Roles Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zoneRolesViewer</code> )</p>
<p>Read-only access to Roles in the zone.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.zones.listRoles</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zoneViewer" class="role-title add-link" data-text="Edge Container Zone Viewer" tabindex="-1">Edge Container Zone Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p>Read-only access to zones.</p></td>
<td><p><code dir="ltr" translate="no">edgecontainer.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgecontainer.locations.get</code></li>
<li><code dir="ltr" translate="no">edgecontainer.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgecontainer.operations.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.get</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p></td>
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
<td><h4 id="edgecontainer.clusterServiceAgent" class="role-title add-link" data-text="Edge Container Cluster Service Agent" tabindex="-1">Edge Container Cluster Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</p>
<p>Grants the Edge Container Cluster Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">gkehub.endpoints.connect</code></p>
<p><code dir="ltr" translate="no">gkehub.features.create</code></p>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.list</code></p>
<p><code dir="ltr" translate="no">gkehub.features.update</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.create</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.get</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.create</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.update</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">kubernetesmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  publish</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  snapshot</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.get</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.alerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.alerts.get</code></li>
<li><code dir="ltr" translate="no">monitoring.alerts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.dashboards.create</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.delete</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.update</code></p>
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
<p><code dir="ltr" translate="no">opsconfigmonitoring.*</code></p>
<ul>
<li><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></li>
<li><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  write</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  contentsecuritypolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivemcppolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.mcppolicy.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.resourceMetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></li>
<li><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  write</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceAgent" class="role-title add-link" data-text="Edge Container Service Agent" tabindex="-1">Edge Container Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</p>
<p>Grants the Edge Container Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  externalVpnGateways.  create</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  use</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.create</code></p>
<p><code dir="ltr" translate="no">compute.routers.delete</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.update</code></p>
<p><code dir="ltr" translate="no">compute.routers.use</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.create</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.delete</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.use</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.create</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.delete</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.create</code></p>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.update</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.create</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.update</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.cancel</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
</tr>
</tbody>
</table>

## Distributed Cloud Edge Container permissions

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
<td><h4 id="edgecontainer.apikeys.create" class="permission-name add-link" data-text="edgecontainer.apikeys.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.apikeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.apikeys.delete" class="permission-name add-link" data-text="edgecontainer.apikeys.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.apikeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.apikeys.get" class="permission-name add-link" data-text="edgecontainer.apikeys.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.apikeys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyViewer">Edge Container API Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.apikeys.list" class="permission-name add-link" data-text="edgecontainer.apikeys.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyViewer">Edge Container API Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.clusters.create" class="permission-name add-link" data-text="edgecontainer.clusters.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.clusters.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.clusters.delete" class="permission-name add-link" data-text="edgecontainer.clusters.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.clusters.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.clusters.generateAccessToken" class="permission-name add-link" data-text="edgecontainer.clusters.generateAccessToken" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  clusters.  generateAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.clusters.generateOfflineCredential" class="permission-name add-link" data-text="edgecontainer.clusters.generateOfflineCredential" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  clusters.  generateOfflineCredential</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.offlineCredentialUser">Edge Container Cluster offline Credential User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.offlineCredentialUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.clusters.get" class="permission-name add-link" data-text="edgecontainer.clusters.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.clusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.clusters.getIamPolicy" class="permission-name add-link" data-text="edgecontainer.clusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  clusters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.clusters.list" class="permission-name add-link" data-text="edgecontainer.clusters.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.clusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.clusters.setIamPolicy" class="permission-name add-link" data-text="edgecontainer.clusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  clusters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.clusters.update" class="permission-name add-link" data-text="edgecontainer.clusters.update" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.clusters.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.clusters.upgrade" class="permission-name add-link" data-text="edgecontainer.clusters.upgrade" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.clusters.upgrade</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.identityproviders.create" class="permission-name add-link" data-text="edgecontainer.identityproviders.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  identityproviders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderAdmin">Edge Container Identity Provider Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.identityproviders.delete" class="permission-name add-link" data-text="edgecontainer.identityproviders.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  identityproviders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderAdmin">Edge Container Identity Provider Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.identityproviders.get" class="permission-name add-link" data-text="edgecontainer.identityproviders.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  identityproviders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderAdmin">Edge Container Identity Provider Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderViewer">Edge Container Identity Provider Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.identityproviders.list" class="permission-name add-link" data-text="edgecontainer.identityproviders.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderAdmin">Edge Container Identity Provider Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderViewer">Edge Container Identity Provider Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.locations.get" class="permission-name add-link" data-text="edgecontainer.locations.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyViewer">Edge Container API Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderAdmin">Edge Container Identity Provider Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderViewer">Edge Container Identity Provider Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountAdmin">Edge Container Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountViewer">Edge Container Service Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceViewer">Edge Container Zonal Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamAdmin">Edge Container Zone Iam Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamViewer">Edge Container Zone Iam Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneRolesViewer">Edge Container Roles Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneRolesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneViewer">Edge Container Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.locations.list" class="permission-name add-link" data-text="edgecontainer.locations.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyViewer">Edge Container API Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderAdmin">Edge Container Identity Provider Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.identityProviderViewer">Edge Container Identity Provider Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.identityProviderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountAdmin">Edge Container Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountViewer">Edge Container Service Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceViewer">Edge Container Zonal Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamAdmin">Edge Container Zone Iam Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamViewer">Edge Container Zone Iam Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneRolesViewer">Edge Container Roles Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneRolesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneViewer">Edge Container Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.machines.create" class="permission-name add-link" data-text="edgecontainer.machines.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.machines.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.machines.delete" class="permission-name add-link" data-text="edgecontainer.machines.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.machines.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.machines.get" class="permission-name add-link" data-text="edgecontainer.machines.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.machines.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.machines.getIamPolicy" class="permission-name add-link" data-text="edgecontainer.machines.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.machines.list" class="permission-name add-link" data-text="edgecontainer.machines.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.machines.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.machines.setIamPolicy" class="permission-name add-link" data-text="edgecontainer.machines.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  machines.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.machines.update" class="permission-name add-link" data-text="edgecontainer.machines.update" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.machines.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.machines.use" class="permission-name add-link" data-text="edgecontainer.machines.use" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.machines.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.machineUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.nodePools.create" class="permission-name add-link" data-text="edgecontainer.nodePools.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.nodePools.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.nodePools.delete" class="permission-name add-link" data-text="edgecontainer.nodePools.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.nodePools.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.nodePools.get" class="permission-name add-link" data-text="edgecontainer.nodePools.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.nodePools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.nodePools.getIamPolicy" class="permission-name add-link" data-text="edgecontainer.nodePools.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  nodePools.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.nodePools.list" class="permission-name add-link" data-text="edgecontainer.nodePools.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.nodePools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.nodePools.setIamPolicy" class="permission-name add-link" data-text="edgecontainer.nodePools.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  nodePools.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.nodePools.update" class="permission-name add-link" data-text="edgecontainer.nodePools.update" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.nodePools.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.operations.cancel" class="permission-name add-link" data-text="edgecontainer.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.operations.delete" class="permission-name add-link" data-text="edgecontainer.operations.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.operations.get" class="permission-name add-link" data-text="edgecontainer.operations.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyViewer">Edge Container API Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceViewer">Edge Container Zonal Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneViewer">Edge Container Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.operations.list" class="permission-name add-link" data-text="edgecontainer.operations.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyAdmin">Edge Container API Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.apiKeyViewer">Edge Container API Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.apiKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceViewer">Edge Container Zonal Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneViewer">Edge Container Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serverconfig.get" class="permission-name add-link" data-text="edgecontainer.serverconfig.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.serverconfig.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.serviceaccounts.create" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountAdmin">Edge Container Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceaccounts.delete" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountAdmin">Edge Container Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.serviceaccounts.describekey" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.describekey" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  describekey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyAdmin">Edge Container Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyViewer">Edge Container Service Account Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceaccounts.disablekey" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.disablekey" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  disablekey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyAdmin">Edge Container Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.serviceaccounts.generatekey" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.generatekey" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  generatekey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyAdmin">Edge Container Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceaccounts.get" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountAdmin">Edge Container Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyAdmin">Edge Container Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyViewer">Edge Container Service Account Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountViewer">Edge Container Service Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.serviceaccounts.list" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountAdmin">Edge Container Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyAdmin">Edge Container Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyViewer">Edge Container Service Account Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountViewer">Edge Container Service Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.serviceaccounts.listkeys" class="permission-name add-link" data-text="edgecontainer.serviceaccounts.listkeys" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  listkeys</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyAdmin">Edge Container Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAccountKeyViewer">Edge Container Service Account Key Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAccountKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.vpnConnections.create" class="permission-name add-link" data-text="edgecontainer.vpnConnections.create" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.vpnConnections.delete" class="permission-name add-link" data-text="edgecontainer.vpnConnections.delete" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.vpnConnections.get" class="permission-name add-link" data-text="edgecontainer.vpnConnections.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.vpnConnections.getIamPolicy" class="permission-name add-link" data-text="edgecontainer.vpnConnections.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.vpnConnections.list" class="permission-name add-link" data-text="edgecontainer.vpnConnections.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.vpnConnections.setIamPolicy" class="permission-name add-link" data-text="edgecontainer.vpnConnections.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.vpnConnections.update" class="permission-name add-link" data-text="edgecontainer.vpnConnections.update" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zonalProjects.disable" class="permission-name add-link" data-text="edgecontainer.zonalProjects.disable" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zonalProjects.enable" class="permission-name add-link" data-text="edgecontainer.zonalProjects.enable" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zonalProjects.get" class="permission-name add-link" data-text="edgecontainer.zonalProjects.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zonalProjects.list" class="permission-name add-link" data-text="edgecontainer.zonalProjects.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zonalservices.disable" class="permission-name add-link" data-text="edgecontainer.zonalservices.disable" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalservices.  disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zonalservices.enable" class="permission-name add-link" data-text="edgecontainer.zonalservices.enable" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalservices.  enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zonalservices.get" class="permission-name add-link" data-text="edgecontainer.zonalservices.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalservices.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceViewer">Edge Container Zonal Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zonalservices.list" class="permission-name add-link" data-text="edgecontainer.zonalservices.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceAdmin">Edge Container Zonal Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalServiceViewer">Edge Container Zonal Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zones.get" class="permission-name add-link" data-text="edgecontainer.zones.get" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.zones.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneViewer">Edge Container Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zones.getZoneIamPolicy" class="permission-name add-link" data-text="edgecontainer.zones.getZoneIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zones.  getZoneIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamAdmin">Edge Container Zone Iam Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamViewer">Edge Container Zone Iam Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zones.list" class="permission-name add-link" data-text="edgecontainer.zones.list" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.zones.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectAdmin">Edge Container Zonal Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zonalProjectViewer">Edge Container Zonal Project Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zonalProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneViewer">Edge Container Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgecontainer.zones.listRoles" class="permission-name add-link" data-text="edgecontainer.zones.listRoles" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.zones.listRoles</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamAdmin">Edge Container Zone Iam Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneRolesViewer">Edge Container Roles Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneRolesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgecontainer.zones.setZoneIamPolicy" class="permission-name add-link" data-text="edgecontainer.zones.setZoneIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgecontainer.  zones.  setZoneIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.zoneIamAdmin">Edge Container Zone Iam Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.zoneIamAdmin</code> )</p></td>
</tr>
</tbody>
</table>
