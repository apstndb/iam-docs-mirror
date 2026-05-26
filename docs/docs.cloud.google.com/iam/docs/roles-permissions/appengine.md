---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/appengine
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/appengine
title: App Engine roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for App Engine. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## App Engine roles

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
<td><h4 id="appengine.appAdmin" class="role-title add-link" data-text="App Engine Admin" tabindex="-1">App Engine Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p>Read/Write/Modify access to all application configuration and settings.</p>
<p>To deploy new versions, a principal must have the <a href="https://docs.cloud.google.com/iam/docs/service-account-permissions#user-role">Service Account User</a> ( <code dir="ltr" translate="no">roles/iam.serviceAccountUser</code> ) role on the assigned App Engine <a href="https://docs.cloud.google.com/appengine/docs/standard/configure-service-accounts">service account</a> , and the Cloud Build Editor ( <code dir="ltr" translate="no">roles/cloudbuild.builds.editor</code> ), and Cloud Storage Object Admin ( <code dir="ltr" translate="no">roles/storage.objectAdmin</code> ) roles on the project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.applications.update</code></p>
<p><code dir="ltr" translate="no">appengine.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.instances.delete</code></li>
<li><code dir="ltr" translate="no">appengine.  instances.  enableDebug</code></li>
<li><code dir="ltr" translate="no">appengine.instances.get</code></li>
<li><code dir="ltr" translate="no">appengine.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.memcache.addKey</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.flush</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.get</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.update</code></p>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.runtimes.actAsAdmin</code></p>
<p><code dir="ltr" translate="no">appengine.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.services.delete</code></li>
<li><code dir="ltr" translate="no">appengine.services.get</code></li>
<li><code dir="ltr" translate="no">appengine.services.list</code></li>
<li><code dir="ltr" translate="no">appengine.services.update</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.versions.create</code></p>
<p><code dir="ltr" translate="no">appengine.versions.delete</code></p>
<p><code dir="ltr" translate="no">appengine.  versions.  exportAppImage</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="appengine.appCreator" class="role-title add-link" data-text="App Engine Creator" tabindex="-1">App Engine Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.appCreator</code> )</p>
<p>Ability to create the App Engine resource for the project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.appViewer" class="role-title add-link" data-text="App Engine Viewer" tabindex="-1">App Engine Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p>Read-only access to all application configuration and settings.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.instances.get</code></p>
<p><code dir="ltr" translate="no">appengine.instances.list</code></p>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.services.get</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="appengine.codeViewer" class="role-title add-link" data-text="App Engine Code Viewer" tabindex="-1">App Engine Code Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p>Read-only access to all application configuration, settings, and deployed source code.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.instances.get</code></p>
<p><code dir="ltr" translate="no">appengine.instances.list</code></p>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.services.get</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.  versions.  getFileContents</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.debugger" class="role-title add-link" data-text="App Engine Managed VM Debug Access" tabindex="-1">App Engine Managed VM Debug Access</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p>Ability to read or manage v2 instances.</p></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.instances.delete</code></li>
<li><code dir="ltr" translate="no">appengine.  instances.  enableDebug</code></li>
<li><code dir="ltr" translate="no">appengine.instances.get</code></li>
<li><code dir="ltr" translate="no">appengine.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.services.get</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="appengine.deployer" class="role-title add-link" data-text="App Engine Deployer" tabindex="-1">App Engine Deployer</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p>Read-only access to all application configuration and settings.</p>
<p>To deploy new versions, you must also have the <a href="https://docs.cloud.google.com/iam/docs/service-account-permissions#user-role">Service Account User</a> ( <code dir="ltr" translate="no">roles/iam.serviceAccountUser</code> ) role on the assigned App Engine <a href="https://docs.cloud.google.com/appengine/docs/standard/configure-service-accounts">service account</a> , and the Cloud Build Editor ( <code dir="ltr" translate="no">roles/cloudbuild.builds.editor</code> ), and Cloud Storage Object Admin ( <code dir="ltr" translate="no">roles/storage.objectAdmin</code> ) roles on the project.</p>
<p>Cannot modify existing versions other than deleting versions that are not receiving traffic.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.instances.get</code></p>
<p><code dir="ltr" translate="no">appengine.instances.list</code></p>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.services.get</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.create</code></p>
<p><code dir="ltr" translate="no">appengine.versions.delete</code></p>
<p><code dir="ltr" translate="no">appengine.  versions.  exportAppImage</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.memcacheDataAdmin" class="role-title add-link" data-text="App Engine Memcache Data Admin" tabindex="-1">App Engine Memcache Data Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p>Can get, set, delete, and flush App Engine Memcache items.</p></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.addKey</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.flush</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.get</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="appengine.serviceAdmin" class="role-title add-link" data-text="App Engine Service Admin" tabindex="-1">App Engine Service Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p>Read-only access to all application configuration and settings.</p>
<p>Write access to module-level and version-level settings. Cannot deploy a new version.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></p>
<p><code dir="ltr" translate="no">appengine.instances.delete</code></p>
<p><code dir="ltr" translate="no">appengine.instances.get</code></p>
<p><code dir="ltr" translate="no">appengine.instances.list</code></p>
<p><code dir="ltr" translate="no">appengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.operations.get</code></li>
<li><code dir="ltr" translate="no">appengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">appengine.services.delete</code></li>
<li><code dir="ltr" translate="no">appengine.services.get</code></li>
<li><code dir="ltr" translate="no">appengine.services.list</code></li>
<li><code dir="ltr" translate="no">appengine.services.update</code></li>
</ul>
<p><code dir="ltr" translate="no">appengine.versions.delete</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
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
<td><h4 id="appengine.serviceAgent" class="role-title add-link" data-text="App Engine Standard Environment Service Agent" tabindex="-1">App Engine Standard Environment Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</p>
<p>Give App Engine Standard Envirnoment service account access to managed resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">appengine.versions.delete</code></p>
<p><code dir="ltr" translate="no">appengine.versions.get</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.entities.create</code></p>
<p><code dir="ltr" translate="no">datastore.entities.delete</code></p>
<p><code dir="ltr" translate="no">datastore.entities.get</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.update</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p></td>
</tr>
</tbody>
</table>

## App Engine permissions

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
<td><h4 id="appengine.applications.create" class="permission-name add-link" data-text="appengine.applications.create" tabindex="-1"><code dir="ltr" translate="no">appengine.applications.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appCreator">App Engine Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.applications.get" class="permission-name add-link" data-text="appengine.applications.get" tabindex="-1"><code dir="ltr" translate="no">appengine.applications.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#websecurityscanner.serviceAgent">Cloud Web Security Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  websecurityscanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.applications.listRuntimes" class="permission-name add-link" data-text="appengine.applications.listRuntimes" tabindex="-1"><code dir="ltr" translate="no">appengine.  applications.  listRuntimes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.applications.update" class="permission-name add-link" data-text="appengine.applications.update" tabindex="-1"><code dir="ltr" translate="no">appengine.applications.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.instances.delete" class="permission-name add-link" data-text="appengine.instances.delete" tabindex="-1"><code dir="ltr" translate="no">appengine.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.instances.enableDebug" class="permission-name add-link" data-text="appengine.instances.enableDebug" tabindex="-1"><code dir="ltr" translate="no">appengine.  instances.  enableDebug</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.instances.get" class="permission-name add-link" data-text="appengine.instances.get" tabindex="-1"><code dir="ltr" translate="no">appengine.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.instances.list" class="permission-name add-link" data-text="appengine.instances.list" tabindex="-1"><code dir="ltr" translate="no">appengine.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.memcache.addKey" class="permission-name add-link" data-text="appengine.memcache.addKey" tabindex="-1"><code dir="ltr" translate="no">appengine.memcache.addKey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.memcache.flush" class="permission-name add-link" data-text="appengine.memcache.flush" tabindex="-1"><code dir="ltr" translate="no">appengine.memcache.flush</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.memcache.get" class="permission-name add-link" data-text="appengine.memcache.get" tabindex="-1"><code dir="ltr" translate="no">appengine.memcache.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.memcache.getKey" class="permission-name add-link" data-text="appengine.memcache.getKey" tabindex="-1"><code dir="ltr" translate="no">appengine.memcache.getKey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.memcache.list" class="permission-name add-link" data-text="appengine.memcache.list" tabindex="-1"><code dir="ltr" translate="no">appengine.memcache.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="appengine.memcache.update" class="permission-name add-link" data-text="appengine.memcache.update" tabindex="-1"><code dir="ltr" translate="no">appengine.memcache.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.memcacheDataAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.operations.get" class="permission-name add-link" data-text="appengine.operations.get" tabindex="-1"><code dir="ltr" translate="no">appengine.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.operations.list" class="permission-name add-link" data-text="appengine.operations.list" tabindex="-1"><code dir="ltr" translate="no">appengine.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.runtimes.actAsAdmin" class="permission-name add-link" data-text="appengine.runtimes.actAsAdmin" tabindex="-1"><code dir="ltr" translate="no">appengine.runtimes.actAsAdmin</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.services.delete" class="permission-name add-link" data-text="appengine.services.delete" tabindex="-1"><code dir="ltr" translate="no">appengine.services.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.services.get" class="permission-name add-link" data-text="appengine.services.get" tabindex="-1"><code dir="ltr" translate="no">appengine.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.services.list" class="permission-name add-link" data-text="appengine.services.list" tabindex="-1"><code dir="ltr" translate="no">appengine.services.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.services.update" class="permission-name add-link" data-text="appengine.services.update" tabindex="-1"><code dir="ltr" translate="no">appengine.services.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.versions.create" class="permission-name add-link" data-text="appengine.versions.create" tabindex="-1"><code dir="ltr" translate="no">appengine.versions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.versions.delete" class="permission-name add-link" data-text="appengine.versions.delete" tabindex="-1"><code dir="ltr" translate="no">appengine.versions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.versions.exportAppImage" class="permission-name add-link" data-text="appengine.versions.exportAppImage" tabindex="-1"><code dir="ltr" translate="no">appengine.  versions.  exportAppImage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.versions.get" class="permission-name add-link" data-text="appengine.versions.get" tabindex="-1"><code dir="ltr" translate="no">appengine.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.versions.getFileContents" class="permission-name add-link" data-text="appengine.versions.getFileContents" tabindex="-1"><code dir="ltr" translate="no">appengine.  versions.  getFileContents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="appengine.versions.list" class="permission-name add-link" data-text="appengine.versions.list" tabindex="-1"><code dir="ltr" translate="no">appengine.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="appengine.versions.update" class="permission-name add-link" data-text="appengine.versions.update" tabindex="-1"><code dir="ltr" translate="no">appengine.versions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
