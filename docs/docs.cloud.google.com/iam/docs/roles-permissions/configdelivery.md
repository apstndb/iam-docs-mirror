---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/configdelivery
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery
title: Config Delivery roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Config Delivery. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Config Delivery roles

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
<td><h4 id="configdelivery.admin" class="role-title add-link" data-text="Configdelivery Admin" tabindex="-1">Configdelivery Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p>Admin role for configdelivery</p></td>
<td><p><code dir="ltr" translate="no">configdelivery.*</code></p>
<ul>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  create</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  get</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  update</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">configdelivery.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.operations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.operations.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.create</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.update</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  create</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  get</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  update</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.abort</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.resume</code></li>
<li><code dir="ltr" translate="no">configdelivery.  rollouts.  suspend</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.create</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.viewer" class="role-title add-link" data-text="Configdelivery Viewer" tabindex="-1">Configdelivery Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p>Viewer role for configdelivery</p></td>
<td><p><code dir="ltr" translate="no">configdelivery.  fleetPackages.  get</code></p>
<p><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">configdelivery.locations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">configdelivery.operations.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.operations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  get</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.rollouts.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.rollouts.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.configDeliveryAdmin" class="role-title add-link" data-text="ConfigDelivery Admin" tabindex="-1">ConfigDelivery Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p>Grants full access to all Config Delivery resources. Lets users create, remove and manage fleet packages and resource bundles.</p></td>
<td><p><code dir="ltr" translate="no">configdelivery.*</code></p>
<ul>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  create</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  get</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></li>
<li><code dir="ltr" translate="no">configdelivery.  fleetPackages.  update</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">configdelivery.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.operations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.operations.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.create</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.releases.update</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  create</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  get</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></li>
<li><code dir="ltr" translate="no">configdelivery.  resourceBundles.  update</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.abort</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.rollouts.resume</code></li>
<li><code dir="ltr" translate="no">configdelivery.  rollouts.  suspend</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.create</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.delete</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.list</code></li>
<li><code dir="ltr" translate="no">configdelivery.variants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.configDeliveryViewer" class="role-title add-link" data-text="ConfigDelivery Viewer" tabindex="-1">ConfigDelivery Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p>Grants read access to all Config Delivery resources. Lets users view existing fleet packages and resource bundles, but they will not be able to make any changes.</p></td>
<td><p><code dir="ltr" translate="no">configdelivery.  fleetPackages.  get</code></p>
<p><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">configdelivery.locations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">configdelivery.operations.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.operations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  get</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.rollouts.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.rollouts.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.resourceBundlePublisher" class="role-title add-link" data-text="Config Delivery Resource Bundle Publisher" tabindex="-1">Config Delivery Resource Bundle Publisher</h4>
<p>( <code dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p>Grants read and write permissions to Config Delivery ResourceBundles and Releases.</p></td>
<td><p><code dir="ltr" translate="no">configdelivery.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">configdelivery.locations.get</code></li>
<li><code dir="ltr" translate="no">configdelivery.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">configdelivery.operations.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.operations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.create</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.update</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  create</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  get</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  update</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.create</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.get</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.update</code></p>
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
<td><h4 id="configdelivery.serviceAgent" class="role-title add-link" data-text="Config Delivery Service Agent" tabindex="-1">Config Delivery Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</p>
<p>Gives the Config Delivery service account permission to manage resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.repositories.get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">container.thirdPartyObjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p></td>
</tr>
</tbody>
</table>

## Config Delivery permissions

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
<td><h4 id="configdelivery.fleetPackages.create" class="permission-name add-link" data-text="configdelivery.fleetPackages.create" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  fleetPackages.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.fleetPackages.delete" class="permission-name add-link" data-text="configdelivery.fleetPackages.delete" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  fleetPackages.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.fleetPackages.get" class="permission-name add-link" data-text="configdelivery.fleetPackages.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  fleetPackages.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.fleetPackages.list" class="permission-name add-link" data-text="configdelivery.fleetPackages.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.fleetPackages.update" class="permission-name add-link" data-text="configdelivery.fleetPackages.update" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  fleetPackages.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.locations.get" class="permission-name add-link" data-text="configdelivery.locations.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.locations.list" class="permission-name add-link" data-text="configdelivery.locations.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.operations.cancel" class="permission-name add-link" data-text="configdelivery.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.operations.delete" class="permission-name add-link" data-text="configdelivery.operations.delete" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.operations.get" class="permission-name add-link" data-text="configdelivery.operations.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.operations.list" class="permission-name add-link" data-text="configdelivery.operations.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.releases.create" class="permission-name add-link" data-text="configdelivery.releases.create" tabindex="-1"><code dir="ltr" translate="no">configdelivery.releases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.releases.delete" class="permission-name add-link" data-text="configdelivery.releases.delete" tabindex="-1"><code dir="ltr" translate="no">configdelivery.releases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.releases.get" class="permission-name add-link" data-text="configdelivery.releases.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.releases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.releases.list" class="permission-name add-link" data-text="configdelivery.releases.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.releases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.releases.update" class="permission-name add-link" data-text="configdelivery.releases.update" tabindex="-1"><code dir="ltr" translate="no">configdelivery.releases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.resourceBundles.create" class="permission-name add-link" data-text="configdelivery.resourceBundles.create" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  resourceBundles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.resourceBundles.delete" class="permission-name add-link" data-text="configdelivery.resourceBundles.delete" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  resourceBundles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.resourceBundles.get" class="permission-name add-link" data-text="configdelivery.resourceBundles.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  resourceBundles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.resourceBundles.list" class="permission-name add-link" data-text="configdelivery.resourceBundles.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.resourceBundles.update" class="permission-name add-link" data-text="configdelivery.resourceBundles.update" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  resourceBundles.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.rollouts.abort" class="permission-name add-link" data-text="configdelivery.rollouts.abort" tabindex="-1"><code dir="ltr" translate="no">configdelivery.rollouts.abort</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.rollouts.get" class="permission-name add-link" data-text="configdelivery.rollouts.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.rollouts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.rollouts.list" class="permission-name add-link" data-text="configdelivery.rollouts.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.rollouts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.rollouts.resume" class="permission-name add-link" data-text="configdelivery.rollouts.resume" tabindex="-1"><code dir="ltr" translate="no">configdelivery.rollouts.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.rollouts.suspend" class="permission-name add-link" data-text="configdelivery.rollouts.suspend" tabindex="-1"><code dir="ltr" translate="no">configdelivery.  rollouts.  suspend</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.variants.create" class="permission-name add-link" data-text="configdelivery.variants.create" tabindex="-1"><code dir="ltr" translate="no">configdelivery.variants.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.variants.delete" class="permission-name add-link" data-text="configdelivery.variants.delete" tabindex="-1"><code dir="ltr" translate="no">configdelivery.variants.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.variants.get" class="permission-name add-link" data-text="configdelivery.variants.get" tabindex="-1"><code dir="ltr" translate="no">configdelivery.variants.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="configdelivery.variants.list" class="permission-name add-link" data-text="configdelivery.variants.list" tabindex="-1"><code dir="ltr" translate="no">configdelivery.variants.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="configdelivery.variants.update" class="permission-name add-link" data-text="configdelivery.variants.update" tabindex="-1"><code dir="ltr" translate="no">configdelivery.variants.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.resourceBundlePublisher</code> )</p></td>
</tr>
</tbody>
</table>
