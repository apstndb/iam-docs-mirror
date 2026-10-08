---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/ml
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/ml
title: AI Platform roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for AI Platform. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## AI Platform roles

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
<td>AI Platform Admin
<p>( <code>roles/ ml.admin</code> )</p>
<p>Provides full access to AI Platform resources, and its jobs, operations, models, and versions.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>ml.*</code></p>
<ul>
<li><code>ml.jobs.cancel</code></li>
<li><code>ml.jobs.create</code></li>
<li><code>ml.jobs.get</code></li>
<li><code>ml.jobs.getIamPolicy</code></li>
<li><code>ml.jobs.list</code></li>
<li><code>ml.jobs.setIamPolicy</code></li>
<li><code>ml.jobs.update</code></li>
<li><code>ml.locations.get</code></li>
<li><code>ml.locations.list</code></li>
<li><code>ml.models.create</code></li>
<li><code>ml.models.delete</code></li>
<li><code>ml.models.get</code></li>
<li><code>ml.models.getIamPolicy</code></li>
<li><code>ml.models.list</code></li>
<li><code>ml.models.predict</code></li>
<li><code>ml.models.setIamPolicy</code></li>
<li><code>ml.models.update</code></li>
<li><code>ml.operations.cancel</code></li>
<li><code>ml.operations.get</code></li>
<li><code>ml.operations.list</code></li>
<li><code>ml.projects.getConfig</code></li>
<li><code>ml.studies.create</code></li>
<li><code>ml.studies.delete</code></li>
<li><code>ml.studies.get</code></li>
<li><code>ml.studies.getIamPolicy</code></li>
<li><code>ml.studies.list</code></li>
<li><code>ml.studies.setIamPolicy</code></li>
<li><code>ml.trials.create</code></li>
<li><code>ml.trials.delete</code></li>
<li><code>ml.trials.get</code></li>
<li><code>ml.trials.list</code></li>
<li><code>ml.trials.update</code></li>
<li><code>ml.versions.create</code></li>
<li><code>ml.versions.delete</code></li>
<li><code>ml.versions.get</code></li>
<li><code>ml.versions.list</code></li>
<li><code>ml.versions.predict</code></li>
<li><code>ml.versions.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>AI Platform Editor
<p>( <code>roles/ ml.editor</code> )</p>
<p>Editor role for AI Platform</p></td>
<td><p><code>ml.jobs.cancel</code></p>
<p><code>ml.jobs.create</code></p>
<p><code>ml.jobs.get</code></p>
<p><code>ml.jobs.getIamPolicy</code></p>
<p><code>ml.jobs.list</code></p>
<p><code>ml.jobs.update</code></p>
<p><code>ml.locations.*</code></p>
<ul>
<li><code>ml.locations.get</code></li>
<li><code>ml.locations.list</code></li>
</ul>
<p><code>ml.models.create</code></p>
<p><code>ml.models.delete</code></p>
<p><code>ml.models.get</code></p>
<p><code>ml.models.getIamPolicy</code></p>
<p><code>ml.models.list</code></p>
<p><code>ml.models.predict</code></p>
<p><code>ml.models.update</code></p>
<p><code>ml.operations.*</code></p>
<ul>
<li><code>ml.operations.cancel</code></li>
<li><code>ml.operations.get</code></li>
<li><code>ml.operations.list</code></li>
</ul>
<p><code>ml.projects.getConfig</code></p>
<p><code>ml.studies.create</code></p>
<p><code>ml.studies.delete</code></p>
<p><code>ml.studies.get</code></p>
<p><code>ml.studies.getIamPolicy</code></p>
<p><code>ml.studies.list</code></p>
<p><code>ml.trials.*</code></p>
<ul>
<li><code>ml.trials.create</code></li>
<li><code>ml.trials.delete</code></li>
<li><code>ml.trials.get</code></li>
<li><code>ml.trials.list</code></li>
<li><code>ml.trials.update</code></li>
</ul>
<p><code>ml.versions.*</code></p>
<ul>
<li><code>ml.versions.create</code></li>
<li><code>ml.versions.delete</code></li>
<li><code>ml.versions.get</code></li>
<li><code>ml.versions.list</code></li>
<li><code>ml.versions.predict</code></li>
<li><code>ml.versions.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>AI Platform Viewer
<p>( <code>roles/ ml.viewer</code> )</p>
<p>Provides read-only access to AI Platform resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>ml.jobs.get</code></p>
<p><code>ml.jobs.getIamPolicy</code></p>
<p><code>ml.jobs.list</code></p>
<p><code>ml.locations.*</code></p>
<ul>
<li><code>ml.locations.get</code></li>
<li><code>ml.locations.list</code></li>
</ul>
<p><code>ml.models.get</code></p>
<p><code>ml.models.getIamPolicy</code></p>
<p><code>ml.models.list</code></p>
<p><code>ml.operations.get</code></p>
<p><code>ml.operations.list</code></p>
<p><code>ml.projects.getConfig</code></p>
<p><code>ml.studies.get</code></p>
<p><code>ml.studies.getIamPolicy</code></p>
<p><code>ml.studies.list</code></p>
<p><code>ml.trials.get</code></p>
<p><code>ml.trials.list</code></p>
<p><code>ml.versions.get</code></p>
<p><code>ml.versions.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>AI Platform Developer
<p>( <code>roles/ ml.developer</code> )</p>
<p>Provides ability to use AI Platform resources for creating models, versions, jobs for training and prediction, and sending online prediction requests.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>ml.jobs.create</code></p>
<p><code>ml.jobs.get</code></p>
<p><code>ml.jobs.getIamPolicy</code></p>
<p><code>ml.jobs.list</code></p>
<p><code>ml.locations.*</code></p>
<ul>
<li><code>ml.locations.get</code></li>
<li><code>ml.locations.list</code></li>
</ul>
<p><code>ml.models.create</code></p>
<p><code>ml.models.get</code></p>
<p><code>ml.models.getIamPolicy</code></p>
<p><code>ml.models.list</code></p>
<p><code>ml.models.predict</code></p>
<p><code>ml.operations.get</code></p>
<p><code>ml.operations.list</code></p>
<p><code>ml.projects.getConfig</code></p>
<p><code>ml.studies.*</code></p>
<ul>
<li><code>ml.studies.create</code></li>
<li><code>ml.studies.delete</code></li>
<li><code>ml.studies.get</code></li>
<li><code>ml.studies.getIamPolicy</code></li>
<li><code>ml.studies.list</code></li>
<li><code>ml.studies.setIamPolicy</code></li>
</ul>
<p><code>ml.trials.*</code></p>
<ul>
<li><code>ml.trials.create</code></li>
<li><code>ml.trials.delete</code></li>
<li><code>ml.trials.get</code></li>
<li><code>ml.trials.list</code></li>
<li><code>ml.trials.update</code></li>
</ul>
<p><code>ml.versions.get</code></p>
<p><code>ml.versions.list</code></p>
<p><code>ml.versions.predict</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td>AI Platform Job Owner
<p>( <code>roles/ ml.jobOwner</code> )</p>
<p>Provides full access to all permissions for a particular job resource. This role is automatically granted to the user who creates the job.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Job</li>
</ul></td>
<td><p><code>ml.jobs.*</code></p>
<ul>
<li><code>ml.jobs.cancel</code></li>
<li><code>ml.jobs.create</code></li>
<li><code>ml.jobs.get</code></li>
<li><code>ml.jobs.getIamPolicy</code></li>
<li><code>ml.jobs.list</code></li>
<li><code>ml.jobs.setIamPolicy</code></li>
<li><code>ml.jobs.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>AI Platform Model Owner
<p>( <code>roles/ ml.modelOwner</code> )</p>
<p>Provides full access to the model and its versions. This role is automatically granted to the user who creates the model.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Model</li>
</ul></td>
<td><p><code>ml.models.*</code></p>
<ul>
<li><code>ml.models.create</code></li>
<li><code>ml.models.delete</code></li>
<li><code>ml.models.get</code></li>
<li><code>ml.models.getIamPolicy</code></li>
<li><code>ml.models.list</code></li>
<li><code>ml.models.predict</code></li>
<li><code>ml.models.setIamPolicy</code></li>
<li><code>ml.models.update</code></li>
</ul>
<p><code>ml.versions.*</code></p>
<ul>
<li><code>ml.versions.create</code></li>
<li><code>ml.versions.delete</code></li>
<li><code>ml.versions.get</code></li>
<li><code>ml.versions.list</code></li>
<li><code>ml.versions.predict</code></li>
<li><code>ml.versions.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>AI Platform Model User
<p>( <code>roles/ ml.modelUser</code> )</p>
<p>Provides permissions to read the model and its versions, and use them for prediction.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Model</li>
</ul></td>
<td><p><code>ml.models.get</code></p>
<p><code>ml.models.predict</code></p>
<p><code>ml.versions.get</code></p>
<p><code>ml.versions.list</code></p>
<p><code>ml.versions.predict</code></p></td>
</tr>
<tr class="even">
<td>AI Platform Operation Owner
<p>( <code>roles/ ml.operationOwner</code> )</p>
<p>Provides full access to all permissions for a particular operation resource.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Operation</li>
</ul></td>
<td><p><code>ml.operations.*</code></p>
<ul>
<li><code>ml.operations.cancel</code></li>
<li><code>ml.operations.get</code></li>
<li><code>ml.operations.list</code></li>
</ul></td>
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
<td>AI Platform Service Agent
<p>( <code>roles/ ml.serviceAgent</code> )</p>
<p>AI Platform service agent can act as log writer, Cloud Storage admin, Artifact Registry Reader, BigQuery writer, and service account access token creator.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. attachments. get</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry.files.get</code></p>
<p><code>artifactregistry.files.list</code></p>
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
<p><code>artifactregistry. projectconfigs. get</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. exportArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry.rules.get</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery.jobs.update</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam. serviceAccounts. implicitDelegation</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam.serviceAccounts.signBlob</code></p>
<p><code>iam.serviceAccounts.signJwt</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>orgpolicy.policy.get</code></p>
<p><code>recommender. iamPolicyInsights.*</code></p>
<ul>
<li><code>recommender. iamPolicyInsights. get</code></li>
<li><code>recommender. iamPolicyInsights. list</code></li>
<li><code>recommender. iamPolicyInsights. update</code></li>
</ul>
<p><code>recommender. iamPolicyRecommendations.*</code></p>
<ul>
<li><code>recommender. iamPolicyRecommendations. get</code></li>
<li><code>recommender. iamPolicyRecommendations. list</code></li>
<li><code>recommender. iamPolicyRecommendations. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteInsights. get</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. list</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteRecommendations. get</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. list</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. update</code></li>
</ul>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.anywhereCaches.*</code></p>
<ul>
<li><code>storage.anywhereCaches.create</code></li>
<li><code>storage.anywhereCaches.disable</code></li>
<li><code>storage.anywhereCaches.get</code></li>
<li><code>storage.anywhereCaches.list</code></li>
<li><code>storage.anywhereCaches.pause</code></li>
<li><code>storage.anywhereCaches.resume</code></li>
<li><code>storage.anywhereCaches.update</code></li>
</ul>
<p><code>storage.bucketOperations.*</code></p>
<ul>
<li><code>storage. bucketOperations. cancel</code></li>
<li><code>storage.bucketOperations.get</code></li>
<li><code>storage.bucketOperations.list</code></li>
</ul>
<p><code>storage.buckets.*</code></p>
<ul>
<li><code>storage.buckets.create</code></li>
<li><code>storage. buckets. createTagBinding</code></li>
<li><code>storage.buckets.delete</code></li>
<li><code>storage. buckets. deleteTagBinding</code></li>
<li><code>storage. buckets. enableObjectRetention</code></li>
<li><code>storage.buckets.get</code></li>
<li><code>storage.buckets.getIamPolicy</code></li>
<li><code>storage.buckets.getIpFilter</code></li>
<li><code>storage. buckets. getObjectInsights</code></li>
<li><code>storage.buckets.list</code></li>
<li><code>storage. buckets. listEffectiveTags</code></li>
<li><code>storage. buckets. listTagBindings</code></li>
<li><code>storage.buckets.relocate</code></li>
<li><code>storage.buckets.restore</code></li>
<li><code>storage.buckets.setIamPolicy</code></li>
<li><code>storage.buckets.setIpFilter</code></li>
<li><code>storage.buckets.update</code></li>
<li><code>storage. buckets. viewIntelligenceDetails</code></li>
<li><code>storage. buckets. viewSecurityIntelligenceDetails</code></li>
</ul>
<p><code>storage.featureConfigs.*</code></p>
<ul>
<li><code>storage.featureConfigs.create</code></li>
<li><code>storage.featureConfigs.delete</code></li>
<li><code>storage.featureConfigs.get</code></li>
<li><code>storage.featureConfigs.list</code></li>
<li><code>storage.featureConfigs.update</code></li>
</ul>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.intelligenceConfigs.*</code></p>
<ul>
<li><code>storage. intelligenceConfigs. get</code></li>
<li><code>storage. intelligenceConfigs. update</code></li>
</ul>
<p><code>storage.managedFolders.*</code></p>
<ul>
<li><code>storage.managedFolders.create</code></li>
<li><code>storage.managedFolders.delete</code></li>
<li><code>storage.managedFolders.get</code></li>
<li><code>storage. managedFolders. getIamPolicy</code></li>
<li><code>storage.managedFolders.list</code></li>
<li><code>storage. managedFolders. setIamPolicy</code></li>
<li><code>storage.managedFolders.update</code></li>
</ul>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.*</code></p>
<ul>
<li><code>storage.objects.create</code></li>
<li><code>storage.objects.createContext</code></li>
<li><code>storage.objects.delete</code></li>
<li><code>storage.objects.deleteContext</code></li>
<li><code>storage.objects.get</code></li>
<li><code>storage.objects.getIamPolicy</code></li>
<li><code>storage.objects.list</code></li>
<li><code>storage.objects.move</code></li>
<li><code>storage. objects. overrideUnlockedRetention</code></li>
<li><code>storage.objects.restore</code></li>
<li><code>storage.objects.setIamPolicy</code></li>
<li><code>storage.objects.setRetention</code></li>
<li><code>storage.objects.update</code></li>
<li><code>storage.objects.updateContext</code></li>
</ul>
<p><code>storagebatchoperations.*</code></p>
<ul>
<li><code>storagebatchoperations. bucketOperations. get</code></li>
<li><code>storagebatchoperations. bucketOperations. list</code></li>
<li><code>storagebatchoperations. jobs. cancel</code></li>
<li><code>storagebatchoperations. jobs. create</code></li>
<li><code>storagebatchoperations. jobs. delete</code></li>
<li><code>storagebatchoperations. jobs. get</code></li>
<li><code>storagebatchoperations. jobs. list</code></li>
<li><code>storagebatchoperations. locations. get</code></li>
<li><code>storagebatchoperations. locations. list</code></li>
<li><code>storagebatchoperations. operations. cancel</code></li>
<li><code>storagebatchoperations. operations. delete</code></li>
<li><code>storagebatchoperations. operations. get</code></li>
<li><code>storagebatchoperations. operations. list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## AI Platform permissions

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
<td><code>ml.jobs.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>ml.jobs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.jobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.jobs.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.jobs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.jobs.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><code>ml.jobs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code>roles/ ml.jobOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>ml.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.models.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.models.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.models.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code>roles/ ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.models.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.models.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.models.predict</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code>roles/ ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.models.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.models.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.operationOwner">AI Platform Operation Owner</a> ( <code>roles/ ml.operationOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><code>ml.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.operationOwner">AI Platform Operation Owner</a> ( <code>roles/ ml.operationOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.operationOwner">AI Platform Operation Owner</a> ( <code>roles/ ml.operationOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.projects.getConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.studies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.studies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.studies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.studies.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.studies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.studies.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.trials.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.trials.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.trials.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.trials.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.trials.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.versions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.versions.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.versions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code>roles/ ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.versions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code>roles/ ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ml.versions.predict</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code>roles/ ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>ml.versions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code>roles/ ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
