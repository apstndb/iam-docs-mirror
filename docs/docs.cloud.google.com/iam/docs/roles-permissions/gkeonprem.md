---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem
title: Google Distributed Cloud roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Distributed Cloud. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Distributed Cloud roles

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
<td><h4 id="gkeonprem.admin" class="role-title add-link" data-text="GKE on-prem Admin" tabindex="-1">GKE on-prem Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p>Full access to GKE on-prem all resources.</p></td>
<td><p><code dir="ltr" translate="no">gkeonprem.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  connect</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  create</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  enroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  queryVersionConfig</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  unenroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  create</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  delete</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  enroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  queryVersionConfig</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  unenroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  create</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  delete</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  enroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  unenroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  update</code></li>
<li><code dir="ltr" translate="no">gkeonprem.locations.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.locations.list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  connect</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  enroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  unenroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  create</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  delete</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  enroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.vmwareClusters.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.vmwareClusters.list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  queryVersionConfig</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  unenroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  create</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  delete</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  enroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.list</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  unenroll</code></li>
<li><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.editor" class="role-title add-link" data-text="Gkeonprem Editor" tabindex="-1">Gkeonprem Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Editor role for gkeonprem</p></td>
<td><p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  connect</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  create</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  queryVersionConfig</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  create</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  queryVersionConfig</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  create</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  delete</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  update</code></p>
<p><code dir="ltr" translate="no">gkeonprem.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkeonprem.locations.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkeonprem.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkeonprem.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  connect</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  create</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  queryVersionConfig</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  create</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  delete</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.viewer" class="role-title add-link" data-text="GKE on-prem Viewer" tabindex="-1">GKE on-prem Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p>Read-only access to GKE on-prem all resources.</p></td>
<td><p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  connect</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  queryVersionConfig</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  queryVersionConfig</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkeonprem.locations.get</code></li>
<li><code dir="ltr" translate="no">gkeonprem.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkeonprem.operations.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.operations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  connect</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  queryVersionConfig</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.list</code></p>
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
<td><h4 id="gkeonprem.serviceAgent" class="role-title add-link" data-text="GKE On-Prem Service Agent" tabindex="-1">GKE On-Prem Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</p>
<p>Gives the GKE On-Prem service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">gkehub.memberships.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.update</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  connect</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.operations.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.operations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  connect</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  unenroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  enroll</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.get</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  unenroll</code></p></td>
</tr>
</tbody>
</table>

## Google Distributed Cloud permissions

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
<td><h4 id="gkeonprem.bareMetalAdminClusters.connect" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.connect" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.create" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.create" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalAdminClusters.createTagBinding" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.deleteTagBinding" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalAdminClusters.enroll" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.enroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  enroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.get" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalAdminClusters.getIamPolicy" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.list" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalAdminClusters.listEffectiveTags" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.listTagBindings" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalAdminClusters.queryVersionConfig" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.queryVersionConfig" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  queryVersionConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.setIamPolicy" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalAdminClusters.unenroll" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.unenroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  unenroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalAdminClusters.update" class="permission-name add-link" data-text="gkeonprem.bareMetalAdminClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.create" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.create" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.createTagBinding" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.delete" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.delete" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.deleteTagBinding" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.enroll" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.enroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  enroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.get" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.getIamPolicy" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.list" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.listEffectiveTags" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.listTagBindings" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.queryVersionConfig" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.queryVersionConfig" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  queryVersionConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.setIamPolicy" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalClusters.unenroll" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.unenroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  unenroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalClusters.update" class="permission-name add-link" data-text="gkeonprem.bareMetalClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalNodePools.create" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.create" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalNodePools.delete" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.delete" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalNodePools.enroll" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.enroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  enroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalNodePools.get" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalNodePools.getIamPolicy" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalNodePools.list" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalNodePools.setIamPolicy" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.bareMetalNodePools.unenroll" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.unenroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  unenroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.bareMetalNodePools.update" class="permission-name add-link" data-text="gkeonprem.bareMetalNodePools.update" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.locations.get" class="permission-name add-link" data-text="gkeonprem.locations.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.locations.list" class="permission-name add-link" data-text="gkeonprem.locations.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.operations.cancel" class="permission-name add-link" data-text="gkeonprem.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.operations.delete" class="permission-name add-link" data-text="gkeonprem.operations.delete" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.operations.get" class="permission-name add-link" data-text="gkeonprem.operations.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.operations.list" class="permission-name add-link" data-text="gkeonprem.operations.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareAdminClusters.connect" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.connect" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareAdminClusters.createTagBinding" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareAdminClusters.deleteTagBinding" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareAdminClusters.enroll" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.enroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  enroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareAdminClusters.get" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareAdminClusters.getIamPolicy" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareAdminClusters.list" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareAdminClusters.listEffectiveTags" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareAdminClusters.listTagBindings" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareAdminClusters.setIamPolicy" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareAdminClusters.unenroll" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.unenroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  unenroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareAdminClusters.update" class="permission-name add-link" data-text="gkeonprem.vmwareAdminClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.create" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.create" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.createTagBinding" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.delete" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.delete" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.deleteTagBinding" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.enroll" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.enroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  enroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.get" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.vmwareClusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.getIamPolicy" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.list" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.vmwareClusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.listEffectiveTags" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.listTagBindings" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.queryVersionConfig" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.queryVersionConfig" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  queryVersionConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.setIamPolicy" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareClusters.unenroll" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.unenroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  unenroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareClusters.update" class="permission-name add-link" data-text="gkeonprem.vmwareClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareNodePools.create" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.create" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareNodePools.delete" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.delete" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareNodePools.enroll" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.enroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  enroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareNodePools.get" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.get" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareNodePools.getIamPolicy" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareNodePools.list" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.list" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareNodePools.setIamPolicy" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkeonprem.vmwareNodePools.unenroll" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.unenroll" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  unenroll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkeonprem.vmwareNodePools.update" class="permission-name add-link" data-text="gkeonprem.vmwareNodePools.update" tabindex="-1"><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkeonprem.editor</code> )</p></td>
</tr>
</tbody>
</table>
