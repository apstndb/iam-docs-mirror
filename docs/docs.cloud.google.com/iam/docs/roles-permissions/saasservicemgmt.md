---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt
title: SaaS Service Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for SaaS Service Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## SaaS Service Management roles

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
<td><h4 id="saasservicemgmt.admin" class="role-title add-link" data-text="SaaS Service Management Admin" tabindex="-1">SaaS Service Management Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Provide full access to all SaaS Service Management resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.flags.create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.flags.delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.flags.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.flags.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.flags.update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.locations.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.locations.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.operations.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  operations.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  releases.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  releases.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.releases.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.releases.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  releases.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.rollouts.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.rollouts.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.saas.create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.saas.delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.saas.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.saas.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.saas.update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.unitKinds.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.unitKinds.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  update</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.viewer" class="role-title add-link" data-text="SaaS Service Management Viewer" tabindex="-1">SaaS Service Management Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p>Provides read-only access to SaaS Service Management resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.locations.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">saasservicemgmt.operations.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  operations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.releases.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.releases.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.rollouts.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.rollouts.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.tenants.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.tenants.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.unitKinds.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.unitKinds.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.units.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.units.list</code></p></td>
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
<td><h4 id="saasservicemgmt.serviceAgent" class="role-title add-link" data-text="SaaS Service Management Service Agent" tabindex="-1">SaaS Service Management Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</p>
<p>Service Agent used by SaaS Service Management.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">apphub.applications.create</code></p>
<p><code dir="ltr" translate="no">apphub.applications.get</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.list</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredServices.  register</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  register</code></p>
<p><code dir="ltr" translate="no">apphub.operations.get</code></p>
<p><code dir="ltr" translate="no">apphub.services.create</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">config.deployments.create</code></p>
<p><code dir="ltr" translate="no">config.deployments.delete</code></p>
<p><code dir="ltr" translate="no">config.deployments.get</code></p>
<p><code dir="ltr" translate="no">config.deployments.getState</code></p>
<p><code dir="ltr" translate="no">config.deployments.update</code></p>
<p><code dir="ltr" translate="no">config.operations.get</code></p>
<p><code dir="ltr" translate="no">config.revisions.get</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplateRevisions.  get</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplates.  get</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplates.  update</code></p>
<p><code dir="ltr" translate="no">designcenter.locations.get</code></p>
<p><code dir="ltr" translate="no">designcenter.operations.get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.update</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.locations.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">saasservicemgmt.operations.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  operations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  releases.  create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.releases.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.releases.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  releases.  update</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.rolloutKinds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">saasservicemgmt.rollouts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.rollouts.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.rollouts.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.update</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.tenants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.tenants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  create</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.unitKinds.get</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.unitKinds.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  update</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">saasservicemgmt.units.*</code></p>
<ul>
<li><code dir="ltr" translate="no">saasservicemgmt.units.create</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.delete</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.get</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.list</code></li>
<li><code dir="ltr" translate="no">saasservicemgmt.units.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## SaaS Service Management permissions

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
<td><h4 id="saasservicemgmt.flagAttributes.create" class="permission-name add-link" data-text="saasservicemgmt.flagAttributes.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagAttributes.delete" class="permission-name add-link" data-text="saasservicemgmt.flagAttributes.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagAttributes.get" class="permission-name add-link" data-text="saasservicemgmt.flagAttributes.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagAttributes.list" class="permission-name add-link" data-text="saasservicemgmt.flagAttributes.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagAttributes.update" class="permission-name add-link" data-text="saasservicemgmt.flagAttributes.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagReleases.create" class="permission-name add-link" data-text="saasservicemgmt.flagReleases.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagReleases.delete" class="permission-name add-link" data-text="saasservicemgmt.flagReleases.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagReleases.get" class="permission-name add-link" data-text="saasservicemgmt.flagReleases.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagReleases.list" class="permission-name add-link" data-text="saasservicemgmt.flagReleases.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagReleases.update" class="permission-name add-link" data-text="saasservicemgmt.flagReleases.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagRevisions.create" class="permission-name add-link" data-text="saasservicemgmt.flagRevisions.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagRevisions.delete" class="permission-name add-link" data-text="saasservicemgmt.flagRevisions.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagRevisions.get" class="permission-name add-link" data-text="saasservicemgmt.flagRevisions.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flagRevisions.list" class="permission-name add-link" data-text="saasservicemgmt.flagRevisions.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flagRevisions.update" class="permission-name add-link" data-text="saasservicemgmt.flagRevisions.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flags.create" class="permission-name add-link" data-text="saasservicemgmt.flags.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.flags.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flags.delete" class="permission-name add-link" data-text="saasservicemgmt.flags.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.flags.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flags.get" class="permission-name add-link" data-text="saasservicemgmt.flags.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.flags.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.flags.list" class="permission-name add-link" data-text="saasservicemgmt.flags.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.flags.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.flags.update" class="permission-name add-link" data-text="saasservicemgmt.flags.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.flags.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.locations.get" class="permission-name add-link" data-text="saasservicemgmt.locations.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.locations.list" class="permission-name add-link" data-text="saasservicemgmt.locations.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.operations.cancel" class="permission-name add-link" data-text="saasservicemgmt.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.operations.delete" class="permission-name add-link" data-text="saasservicemgmt.operations.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.operations.get" class="permission-name add-link" data-text="saasservicemgmt.operations.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.operations.list" class="permission-name add-link" data-text="saasservicemgmt.operations.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.releases.create" class="permission-name add-link" data-text="saasservicemgmt.releases.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  releases.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.releases.delete" class="permission-name add-link" data-text="saasservicemgmt.releases.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  releases.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.releases.get" class="permission-name add-link" data-text="saasservicemgmt.releases.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.releases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.releases.list" class="permission-name add-link" data-text="saasservicemgmt.releases.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.releases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.releases.update" class="permission-name add-link" data-text="saasservicemgmt.releases.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  releases.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.rolloutKinds.create" class="permission-name add-link" data-text="saasservicemgmt.rolloutKinds.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.rolloutKinds.delete" class="permission-name add-link" data-text="saasservicemgmt.rolloutKinds.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.rolloutKinds.get" class="permission-name add-link" data-text="saasservicemgmt.rolloutKinds.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.rolloutKinds.list" class="permission-name add-link" data-text="saasservicemgmt.rolloutKinds.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.rolloutKinds.update" class="permission-name add-link" data-text="saasservicemgmt.rolloutKinds.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.rollouts.create" class="permission-name add-link" data-text="saasservicemgmt.rollouts.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.rollouts.delete" class="permission-name add-link" data-text="saasservicemgmt.rollouts.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.rollouts.get" class="permission-name add-link" data-text="saasservicemgmt.rollouts.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.rollouts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.rollouts.list" class="permission-name add-link" data-text="saasservicemgmt.rollouts.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.rollouts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.rollouts.update" class="permission-name add-link" data-text="saasservicemgmt.rollouts.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  rollouts.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.saas.create" class="permission-name add-link" data-text="saasservicemgmt.saas.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.saas.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.saas.delete" class="permission-name add-link" data-text="saasservicemgmt.saas.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.saas.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.saas.get" class="permission-name add-link" data-text="saasservicemgmt.saas.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.saas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.saas.list" class="permission-name add-link" data-text="saasservicemgmt.saas.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.saas.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.saas.update" class="permission-name add-link" data-text="saasservicemgmt.saas.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.saas.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.tenants.create" class="permission-name add-link" data-text="saasservicemgmt.tenants.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.tenants.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.tenants.delete" class="permission-name add-link" data-text="saasservicemgmt.tenants.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.tenants.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.tenants.get" class="permission-name add-link" data-text="saasservicemgmt.tenants.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.tenants.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.tenants.list" class="permission-name add-link" data-text="saasservicemgmt.tenants.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.tenants.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.tenants.update" class="permission-name add-link" data-text="saasservicemgmt.tenants.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.tenants.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.unitKinds.create" class="permission-name add-link" data-text="saasservicemgmt.unitKinds.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.unitKinds.delete" class="permission-name add-link" data-text="saasservicemgmt.unitKinds.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.unitKinds.get" class="permission-name add-link" data-text="saasservicemgmt.unitKinds.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.unitKinds.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.unitKinds.list" class="permission-name add-link" data-text="saasservicemgmt.unitKinds.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.unitKinds.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.unitKinds.update" class="permission-name add-link" data-text="saasservicemgmt.unitKinds.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitKinds.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.unitOperations.create" class="permission-name add-link" data-text="saasservicemgmt.unitOperations.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.unitOperations.delete" class="permission-name add-link" data-text="saasservicemgmt.unitOperations.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.unitOperations.get" class="permission-name add-link" data-text="saasservicemgmt.unitOperations.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.unitOperations.list" class="permission-name add-link" data-text="saasservicemgmt.unitOperations.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.unitOperations.update" class="permission-name add-link" data-text="saasservicemgmt.unitOperations.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.units.create" class="permission-name add-link" data-text="saasservicemgmt.units.create" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.units.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.units.delete" class="permission-name add-link" data-text="saasservicemgmt.units.delete" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.units.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.units.get" class="permission-name add-link" data-text="saasservicemgmt.units.get" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.units.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="saasservicemgmt.units.list" class="permission-name add-link" data-text="saasservicemgmt.units.list" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.units.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="saasservicemgmt.units.update" class="permission-name add-link" data-text="saasservicemgmt.units.update" tabindex="-1"><code dir="ltr" translate="no">saasservicemgmt.units.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
