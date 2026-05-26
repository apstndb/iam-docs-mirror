---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gkehub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub
title: GKE Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for GKE Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## GKE Hub roles

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
<td><h4 id="gkehub.admin" class="role-title add-link" data-text="Fleet Admin (formerly GKE Hub Admin)" tabindex="-1">Fleet Admin (formerly GKE Hub Admin)</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p>Full access to Fleet resources.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.features.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.features.create</code></li>
<li><code dir="ltr" translate="no">gkehub.features.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.features.get</code></li>
<li><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.features.list</code></li>
<li><code dir="ltr" translate="no">gkehub.features.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.features.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.fleet.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.fleet.create</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.createFreeTrial</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.get</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.getFreeTrial</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.update</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.updateFreeTrial</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  create</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  delete</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipbindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  create</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  delete</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipfeatures.get</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.memberships.create</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.get</code></li>
<li><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  memberships.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.namespaces.create</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.get</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.list</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.create</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.scopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.scopes.create</code></li>
<li><code dir="ltr" translate="no">gkehub.scopes.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.scopes.get</code></li>
<li><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.scopes.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></li>
<li><code dir="ltr" translate="no">gkehub.scopes.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.scopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.editor" class="role-title add-link" data-text="Fleet Editor (formerly GKE Hub Editor)" tabindex="-1">Fleet Editor (formerly GKE Hub Editor)</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Edit access to Fleet resources.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.features.create</code></p>
<p><code dir="ltr" translate="no">gkehub.features.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.features.list</code></p>
<p><code dir="ltr" translate="no">gkehub.features.update</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.fleet.create</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.createFreeTrial</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.get</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.getFreeTrial</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.update</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.updateFreeTrial</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  create</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  delete</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipbindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  create</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  delete</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipfeatures.get</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.create</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.update</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.namespaces.create</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.get</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.list</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.create</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.scopes.create</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.get</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.viewer" class="role-title add-link" data-text="Fleet Viewer (formerly GKE Hub Viewer)" tabindex="-1">Fleet Viewer (formerly GKE Hub Viewer)</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p>Read-only access to Fleets and related resources.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.features.list</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.get</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.getFreeTrial</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.get</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.get</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.get</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.list</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.get</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.list</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.get</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.connect" class="role-title add-link" data-text="GKE Connect Agent" tabindex="-1">GKE Connect Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.connect</code> )</p>
<p>Ability to set up GKE Connect between external clusters and Google.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.endpoints.connect</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.gatewayAdmin" class="role-title add-link" data-text="Connect Gateway Admin" tabindex="-1">Connect Gateway Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p>Full access to Connect Gateway.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.gateway.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.gateway.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.get</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.patch</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.post</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.put</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.stream</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.gatewayEditor" class="role-title add-link" data-text="Connect Gateway Editor" tabindex="-1">Connect Gateway Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p>Edit access to Connect Gateway.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.gatewayReader" class="role-title add-link" data-text="Connect Gateway Reader" tabindex="-1">Connect Gateway Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.gatewayReader</code> )</p>
<p>Read-only access to Connect Gateway.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopeAdmin" class="role-title add-link" data-text="Fleet Scope Admin" tabindex="-1">Fleet Scope Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p>Admin access to Fleet Scopes to set IAM Bindings and RBACRoleBindings.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.namespaces.create</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.get</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.list</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.create</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.scopes.get</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.setIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.scopeEditor" class="role-title add-link" data-text="Fleet Scope Editor" tabindex="-1">Fleet Scope Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p>Edit access to Namespaces under Fleet Scopes.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.namespaces.create</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.get</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.list</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.get</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopeEditorProjectLevel" class="role-title add-link" data-text="Fleet Project-level Scope Editor" tabindex="-1">Fleet Project-level Scope Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p>Role for project-level permissions for editor of Fleet Scopes.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.get</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.scopeViewer" class="role-title add-link" data-text="Fleet Scope Viewer" tabindex="-1">Fleet Scope Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p>Viewer of Fleet Scopes and associated resources.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.namespaces.get</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.list</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.get</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopeViewerProjectLevel" class="role-title add-link" data-text="Fleet Project-level Scope Viewer" tabindex="-1">Fleet Project-level Scope Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.scopeViewerProjectLevel</code> )</p>
<p>Role for project-level permissions for viewer of Fleet Scopes.</p></td>
<td><p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
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
<td><h4 id="gkehub.crossProjectServiceAgent" class="role-title add-link" data-text="GKE Hub Cross Project Service Agent" tabindex="-1">GKE Hub Cross Project Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.crossProjectServiceAgent</code> )</p>
<p>Gives the GKE Hub service agent permission to manage the project for cross-project fleet registration.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.serviceAgent" class="role-title add-link" data-text="GKE Hub Service Agent" tabindex="-1">GKE Hub Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</p>
<p>Gives the GKE Hub service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">container.  clusterRoleBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusterRoles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusters.connect</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.update</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></p>
<p><code dir="ltr" translate="no">container.namespaces.get</code></p>
<p><code dir="ltr" translate="no">container.operations.get</code></p>
<p><code dir="ltr" translate="no">container.thirdPartyObjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.features.create</code></p>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.list</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.create</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.create</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.create</code></p>
<p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.buckets.update</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.exclusions.create</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.delete</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.get</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.list</code></li>
<li><code dir="ltr" translate="no">logging.exclusions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.sinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.sinks.create</code></li>
<li><code dir="ltr" translate="no">logging.sinks.delete</code></li>
<li><code dir="ltr" translate="no">logging.sinks.get</code></li>
<li><code dir="ltr" translate="no">logging.sinks.list</code></li>
<li><code dir="ltr" translate="no">logging.sinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.views.create</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">logging.views.update</code></p>
<p><code dir="ltr" translate="no">monitoring.metricsScopes.link</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## GKE Hub permissions

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
<td><h4 id="gkehub.endpoints.connect" class="permission-name add-link" data-text="gkehub.endpoints.connect" tabindex="-1"><code dir="ltr" translate="no">gkehub.endpoints.connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.velostrataconnect">Velostrata Manager Connection Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.velostrataconnect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.connect">GKE Connect Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.connect</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.features.create" class="permission-name add-link" data-text="gkehub.features.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.features.delete" class="permission-name add-link" data-text="gkehub.features.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.features.get" class="permission-name add-link" data-text="gkehub.features.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosaudit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.features.getIamPolicy" class="permission-name add-link" data-text="gkehub.features.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.features.list" class="permission-name add-link" data-text="gkehub.features.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.features.setIamPolicy" class="permission-name add-link" data-text="gkehub.features.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.features.update" class="permission-name add-link" data-text="gkehub.features.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.features.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.fleet.create" class="permission-name add-link" data-text="gkehub.fleet.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.fleet.createFreeTrial" class="permission-name add-link" data-text="gkehub.fleet.createFreeTrial" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.createFreeTrial</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.fleet.delete" class="permission-name add-link" data-text="gkehub.fleet.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.fleet.get" class="permission-name add-link" data-text="gkehub.fleet.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.fleet.getFreeTrial" class="permission-name add-link" data-text="gkehub.fleet.getFreeTrial" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.getFreeTrial</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.fleet.update" class="permission-name add-link" data-text="gkehub.fleet.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.fleet.updateFreeTrial" class="permission-name add-link" data-text="gkehub.fleet.updateFreeTrial" tabindex="-1"><code dir="ltr" translate="no">gkehub.fleet.updateFreeTrial</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.gateway.delete" class="permission-name add-link" data-text="gkehub.gateway.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.gateway.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.gateway.generateCredentials" class="permission-name add-link" data-text="gkehub.gateway.generateCredentials" tabindex="-1"><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.gateway.get" class="permission-name add-link" data-text="gkehub.gateway.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.gateway.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.gateway.patch" class="permission-name add-link" data-text="gkehub.gateway.patch" tabindex="-1"><code dir="ltr" translate="no">gkehub.gateway.patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.gateway.post" class="permission-name add-link" data-text="gkehub.gateway.post" tabindex="-1"><code dir="ltr" translate="no">gkehub.gateway.post</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.gateway.put" class="permission-name add-link" data-text="gkehub.gateway.put" tabindex="-1"><code dir="ltr" translate="no">gkehub.gateway.put</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.gateway.stream" class="permission-name add-link" data-text="gkehub.gateway.stream" tabindex="-1"><code dir="ltr" translate="no">gkehub.gateway.stream</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.locations.get" class="permission-name add-link" data-text="gkehub.locations.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosaudit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.locations.list" class="permission-name add-link" data-text="gkehub.locations.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosaudit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.membershipbindings.create" class="permission-name add-link" data-text="gkehub.membershipbindings.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.  membershipbindings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.membershipbindings.delete" class="permission-name add-link" data-text="gkehub.membershipbindings.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.  membershipbindings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.membershipbindings.get" class="permission-name add-link" data-text="gkehub.membershipbindings.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.membershipbindings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.membershipbindings.list" class="permission-name add-link" data-text="gkehub.membershipbindings.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.membershipbindings.update" class="permission-name add-link" data-text="gkehub.membershipbindings.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.  membershipbindings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.membershipfeatures.create" class="permission-name add-link" data-text="gkehub.membershipfeatures.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.  membershipfeatures.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.membershipfeatures.delete" class="permission-name add-link" data-text="gkehub.membershipfeatures.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.  membershipfeatures.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.membershipfeatures.get" class="permission-name add-link" data-text="gkehub.membershipfeatures.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.membershipfeatures.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.membershipfeatures.list" class="permission-name add-link" data-text="gkehub.membershipfeatures.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.membershipfeatures.update" class="permission-name add-link" data-text="gkehub.membershipfeatures.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.  membershipfeatures.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.memberships.create" class="permission-name add-link" data-text="gkehub.memberships.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.memberships.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.memberships.delete" class="permission-name add-link" data-text="gkehub.memberships.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.memberships.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.memberships.generateConnectManifest" class="permission-name add-link" data-text="gkehub.memberships.generateConnectManifest" tabindex="-1"><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.memberships.get" class="permission-name add-link" data-text="gkehub.memberships.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.memberships.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosaudit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.memberships.getIamPolicy" class="permission-name add-link" data-text="gkehub.memberships.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.memberships.list" class="permission-name add-link" data-text="gkehub.memberships.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.memberships.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosaudit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosconfigmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosidentityservice.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthospolicycontroller.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appdevelopmentexperience.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclustermetering.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.memberships.setIamPolicy" class="permission-name add-link" data-text="gkehub.memberships.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkehub.  memberships.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.memberships.update" class="permission-name add-link" data-text="gkehub.memberships.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.memberships.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.namespaces.create" class="permission-name add-link" data-text="gkehub.namespaces.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.namespaces.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.namespaces.delete" class="permission-name add-link" data-text="gkehub.namespaces.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.namespaces.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.namespaces.get" class="permission-name add-link" data-text="gkehub.namespaces.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.namespaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.namespaces.list" class="permission-name add-link" data-text="gkehub.namespaces.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.namespaces.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.namespaces.update" class="permission-name add-link" data-text="gkehub.namespaces.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.namespaces.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.operations.cancel" class="permission-name add-link" data-text="gkehub.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">gkehub.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.operations.delete" class="permission-name add-link" data-text="gkehub.operations.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.operations.get" class="permission-name add-link" data-text="gkehub.operations.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.operations.list" class="permission-name add-link" data-text="gkehub.operations.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.rbacrolebindings.create" class="permission-name add-link" data-text="gkehub.rbacrolebindings.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.rbacrolebindings.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.rbacrolebindings.delete" class="permission-name add-link" data-text="gkehub.rbacrolebindings.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.rbacrolebindings.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.rbacrolebindings.get" class="permission-name add-link" data-text="gkehub.rbacrolebindings.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.rbacrolebindings.list" class="permission-name add-link" data-text="gkehub.rbacrolebindings.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.rbacrolebindings.update" class="permission-name add-link" data-text="gkehub.rbacrolebindings.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.rbacrolebindings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.scopes.create" class="permission-name add-link" data-text="gkehub.scopes.create" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopes.delete" class="permission-name add-link" data-text="gkehub.scopes.delete" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.scopes.get" class="permission-name add-link" data-text="gkehub.scopes.get" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopes.getIamPolicy" class="permission-name add-link" data-text="gkehub.scopes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.scopes.list" class="permission-name add-link" data-text="gkehub.scopes.list" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopes.listBoundMemberships" class="permission-name add-link" data-text="gkehub.scopes.listBoundMemberships" tabindex="-1"><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditor">Fleet Scope Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewer">Fleet Scope Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkehub.scopes.setIamPolicy" class="permission-name add-link" data-text="gkehub.scopes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeAdmin">Fleet Scope Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.scopeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkehub.scopes.update" class="permission-name add-link" data-text="gkehub.scopes.update" tabindex="-1"><code dir="ltr" translate="no">gkehub.scopes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
