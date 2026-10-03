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
<td>Appengine Admin
<p>( <code>roles/ appengine.admin</code> )</p>
<p>Admin role for appengine</p></td>
<td><p><code>appengine.*</code></p>
<ul>
<li><code>appengine.applications.create</code></li>
<li><code>appengine.applications.get</code></li>
<li><code>appengine. applications. listRuntimes</code></li>
<li><code>appengine.applications.update</code></li>
<li><code>appengine.instances.delete</code></li>
<li><code>appengine. instances. enableDebug</code></li>
<li><code>appengine.instances.get</code></li>
<li><code>appengine.instances.list</code></li>
<li><code>appengine.memcache.addKey</code></li>
<li><code>appengine.memcache.flush</code></li>
<li><code>appengine.memcache.get</code></li>
<li><code>appengine.memcache.getKey</code></li>
<li><code>appengine.memcache.list</code></li>
<li><code>appengine.memcache.update</code></li>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
<li><code>appengine.runtimes.actAsAdmin</code></li>
<li><code>appengine.services.delete</code></li>
<li><code>appengine.services.get</code></li>
<li><code>appengine.services.list</code></li>
<li><code>appengine.services.update</code></li>
<li><code>appengine.versions.create</code></li>
<li><code>appengine.versions.delete</code></li>
<li><code>appengine. versions. exportAppImage</code></li>
<li><code>appengine.versions.get</code></li>
<li><code>appengine. versions. getFileContents</code></li>
<li><code>appengine.versions.list</code></li>
<li><code>appengine.versions.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>App Engine Admin
<p>( <code>roles/ appengine.appAdmin</code> )</p>
<p>Read/Write/Modify access to all application configuration and settings.</p>
<p>To deploy new versions, a principal must have the <a href="https://docs.cloud.google.com/iam/docs/service-account-permissions#user-role">Service Account User</a> ( <code>roles/iam.serviceAccountUser</code> ) role on the assigned App Engine <a href="https://docs.cloud.google.com/appengine/docs/standard/configure-service-accounts">service account</a> , and the Cloud Build Editor ( <code>roles/cloudbuild.builds.editor</code> ), and Cloud Storage Object Admin ( <code>roles/storage.objectAdmin</code> ) roles on the project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.applications.update</code></p>
<p><code>appengine.instances.*</code></p>
<ul>
<li><code>appengine.instances.delete</code></li>
<li><code>appengine. instances. enableDebug</code></li>
<li><code>appengine.instances.get</code></li>
<li><code>appengine.instances.list</code></li>
</ul>
<p><code>appengine.memcache.addKey</code></p>
<p><code>appengine.memcache.flush</code></p>
<p><code>appengine.memcache.get</code></p>
<p><code>appengine.memcache.update</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.runtimes.actAsAdmin</code></p>
<p><code>appengine.services.*</code></p>
<ul>
<li><code>appengine.services.delete</code></li>
<li><code>appengine.services.get</code></li>
<li><code>appengine.services.list</code></li>
<li><code>appengine.services.update</code></li>
</ul>
<p><code>appengine.versions.create</code></p>
<p><code>appengine.versions.delete</code></p>
<p><code>appengine. versions. exportAppImage</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>appengine.versions.update</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. repositories. deleteArtifacts</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. uploadArtifacts</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>recommender. appengineVersionCostInsights.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostInsights. get</code></li>
<li><code>recommender. appengineVersionCostInsights. list</code></li>
<li><code>recommender. appengineVersionCostInsights. update</code></li>
</ul>
<p><code>recommender. appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostRecommendations. get</code></li>
<li><code>recommender. appengineVersionCostRecommendations. list</code></li>
<li><code>recommender. appengineVersionCostRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Appengine Editor
<p>( <code>roles/ appengine.editor</code> )</p>
<p>Editor role for appengine</p></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.applications.update</code></p>
<p><code>appengine.instances.*</code></p>
<ul>
<li><code>appengine.instances.delete</code></li>
<li><code>appengine. instances. enableDebug</code></li>
<li><code>appengine.instances.get</code></li>
<li><code>appengine.instances.list</code></li>
</ul>
<p><code>appengine.memcache.*</code></p>
<ul>
<li><code>appengine.memcache.addKey</code></li>
<li><code>appengine.memcache.flush</code></li>
<li><code>appengine.memcache.get</code></li>
<li><code>appengine.memcache.getKey</code></li>
<li><code>appengine.memcache.list</code></li>
<li><code>appengine.memcache.update</code></li>
</ul>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.runtimes.actAsAdmin</code></p>
<p><code>appengine.services.*</code></p>
<ul>
<li><code>appengine.services.delete</code></li>
<li><code>appengine.services.get</code></li>
<li><code>appengine.services.list</code></li>
<li><code>appengine.services.update</code></li>
</ul>
<p><code>appengine.versions.create</code></p>
<p><code>appengine.versions.delete</code></p>
<p><code>appengine. versions. exportAppImage</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>appengine.versions.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Appengine Viewer
<p>( <code>roles/ appengine.viewer</code> )</p>
<p>Viewer role for appengine</p></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.instances.get</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.memcache.get</code></p>
<p><code>appengine.memcache.getKey</code></p>
<p><code>appengine.memcache.list</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.runtimes.actAsAdmin</code></p>
<p><code>appengine.services.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>App Engine Creator
<p>( <code>roles/ appengine.appCreator</code> )</p>
<p>Ability to create the App Engine resource for the project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>appengine.applications.create</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>App Engine Viewer
<p>( <code>roles/ appengine.appViewer</code> )</p>
<p>Read-only access to all application configuration and settings.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.instances.get</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.services.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>recommender. appengineVersionCostInsights. get</code></p>
<p><code>recommender. appengineVersionCostInsights. list</code></p>
<p><code>recommender. appengineVersionCostRecommendations. get</code></p>
<p><code>recommender. appengineVersionCostRecommendations. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>App Engine Code Viewer
<p>( <code>roles/ appengine.codeViewer</code> )</p>
<p>Read-only access to all application configuration, settings, and deployed source code.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.instances.get</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.services.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine. versions. getFileContents</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>App Engine Managed VM Debug Access
<p>( <code>roles/ appengine.debugger</code> )</p>
<p>Ability to read or manage v2 instances.</p></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.instances.*</code></p>
<ul>
<li><code>appengine.instances.delete</code></li>
<li><code>appengine. instances. enableDebug</code></li>
<li><code>appengine.instances.get</code></li>
<li><code>appengine.instances.list</code></li>
</ul>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.services.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>App Engine Deployer
<p>( <code>roles/ appengine.deployer</code> )</p>
<p>Read-only access to all application configuration and settings.</p>
<p>To deploy new versions, you must also have the <a href="https://docs.cloud.google.com/iam/docs/service-account-permissions#user-role">Service Account User</a> ( <code>roles/iam.serviceAccountUser</code> ) role on the assigned App Engine <a href="https://docs.cloud.google.com/appengine/docs/standard/configure-service-accounts">service account</a> , and the Cloud Build Editor ( <code>roles/cloudbuild.builds.editor</code> ), and Cloud Storage Object Admin ( <code>roles/storage.objectAdmin</code> ) roles on the project.</p>
<p>Cannot modify existing versions other than deleting versions that are not receiving traffic.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.instances.get</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.services.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.create</code></p>
<p><code>appengine.versions.delete</code></p>
<p><code>appengine. versions. exportAppImage</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. repositories. deleteArtifacts</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. uploadArtifacts</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>recommender. appengineVersionCostInsights.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostInsights. get</code></li>
<li><code>recommender. appengineVersionCostInsights. list</code></li>
<li><code>recommender. appengineVersionCostInsights. update</code></li>
</ul>
<p><code>recommender. appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostRecommendations. get</code></li>
<li><code>recommender. appengineVersionCostRecommendations. list</code></li>
<li><code>recommender. appengineVersionCostRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>App Engine Memcache Data Admin
<p>( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p>Can get, set, delete, and flush App Engine Memcache items.</p></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine.memcache.addKey</code></p>
<p><code>appengine.memcache.flush</code></p>
<p><code>appengine.memcache.get</code></p>
<p><code>appengine.memcache.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>App Engine Service Admin
<p>( <code>roles/ appengine.serviceAdmin</code> )</p>
<p>Read-only access to all application configuration and settings.</p>
<p>Write access to module-level and version-level settings. Cannot deploy a new version.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>appengine. applications. listRuntimes</code></p>
<p><code>appengine.instances.delete</code></p>
<p><code>appengine.instances.get</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.operations.*</code></p>
<ul>
<li><code>appengine.operations.get</code></li>
<li><code>appengine.operations.list</code></li>
</ul>
<p><code>appengine.services.*</code></p>
<ul>
<li><code>appengine.services.delete</code></li>
<li><code>appengine.services.get</code></li>
<li><code>appengine.services.list</code></li>
<li><code>appengine.services.update</code></li>
</ul>
<p><code>appengine.versions.delete</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>appengine.versions.update</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>recommender. appengineVersionCostInsights.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostInsights. get</code></li>
<li><code>recommender. appengineVersionCostInsights. list</code></li>
<li><code>recommender. appengineVersionCostInsights. update</code></li>
</ul>
<p><code>recommender. appengineVersionCostRecommendations.*</code></p>
<ul>
<li><code>recommender. appengineVersionCostRecommendations. get</code></li>
<li><code>recommender. appengineVersionCostRecommendations. list</code></li>
<li><code>recommender. appengineVersionCostRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>App Engine Standard Environment Service Agent
<p>( <code>roles/ appengine.serviceAgent</code> )</p>
<p>Give App Engine Standard Envirnoment service account access to managed resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>appengine.versions.delete</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>appengine.versions.update</code></p>
<p><code>artifactregistry. aptartifacts. create</code></p>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry.files.get</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry. kfpartifacts. create</code></p>
<p><code>artifactregistry.locations.*</code></p>
<ul>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
</ul>
<p><code>artifactregistry. mavenartifacts.*</code></p>
<ul>
<li><code>artifactregistry. mavenartifacts. get</code></li>
<li><code>artifactregistry. mavenartifacts. list</code></li>
</ul>
<p><code>artifactregistry.npmpackages.*</code></p>
<ul>
<li><code>artifactregistry. npmpackages. get</code></li>
<li><code>artifactregistry. npmpackages. list</code></li>
</ul>
<p><code>artifactregistry.packages.get</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry. repositories. uploadArtifacts</code></p>
<p><code>artifactregistry.tags.create</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.tags.update</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>artifactregistry. yumartifacts. create</code></p>
<p><code>compute.addresses.create</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore.entities.create</code></p>
<p><code>datastore.entities.delete</code></p>
<p><code>datastore.entities.get</code></p>
<p><code>datastore.entities.list</code></p>
<p><code>datastore.entities.update</code></p>
<p><code>datastore.namespaces.*</code></p>
<ul>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
</ul>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.*</code></p>
<ul>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
</ul>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam.serviceAccounts.signBlob</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.get</code></p></td>
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
<td><code>appengine.applications.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appCreator">App Engine Creator</a> ( <code>roles/ appengine.appCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.applications.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code>roles/ datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code>roles/ datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code>roles/ datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code>roles/ datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code>roles/ datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code>roles/ datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code>roles/ datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#websecurityscanner.serviceAgent">Cloud Web Security Scanner Service Agent</a> ( <code>roles/ websecurityscanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine. applications. listRuntimes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.applications.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.instances.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine. instances. enableDebug</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.instances.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.instances.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.memcache.addKey</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.memcache.flush</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.memcache.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.memcache.getKey</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>appengine.memcache.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>appengine.memcache.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.runtimes.actAsAdmin</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.services.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.services.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.services.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.services.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.versions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.versions.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine. versions. exportAppImage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>appengine.versions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine. versions. getFileContents</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>appengine.versions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>appengine.versions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
