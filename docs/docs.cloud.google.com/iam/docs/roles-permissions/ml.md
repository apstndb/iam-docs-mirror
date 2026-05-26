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
<td><h4 id="ml.admin" class="role-title add-link" data-text="AI Platform Admin" tabindex="-1">AI Platform Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p>Provides full access to AI Platform resources, and its jobs, operations, models, and versions.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">ml.jobs.create</code></li>
<li><code dir="ltr" translate="no">ml.jobs.get</code></li>
<li><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.jobs.list</code></li>
<li><code dir="ltr" translate="no">ml.jobs.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.jobs.update</code></li>
<li><code dir="ltr" translate="no">ml.locations.get</code></li>
<li><code dir="ltr" translate="no">ml.locations.list</code></li>
<li><code dir="ltr" translate="no">ml.models.create</code></li>
<li><code dir="ltr" translate="no">ml.models.delete</code></li>
<li><code dir="ltr" translate="no">ml.models.get</code></li>
<li><code dir="ltr" translate="no">ml.models.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.models.list</code></li>
<li><code dir="ltr" translate="no">ml.models.predict</code></li>
<li><code dir="ltr" translate="no">ml.models.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.models.update</code></li>
<li><code dir="ltr" translate="no">ml.operations.cancel</code></li>
<li><code dir="ltr" translate="no">ml.operations.get</code></li>
<li><code dir="ltr" translate="no">ml.operations.list</code></li>
<li><code dir="ltr" translate="no">ml.projects.getConfig</code></li>
<li><code dir="ltr" translate="no">ml.studies.create</code></li>
<li><code dir="ltr" translate="no">ml.studies.delete</code></li>
<li><code dir="ltr" translate="no">ml.studies.get</code></li>
<li><code dir="ltr" translate="no">ml.studies.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.studies.list</code></li>
<li><code dir="ltr" translate="no">ml.studies.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.trials.create</code></li>
<li><code dir="ltr" translate="no">ml.trials.delete</code></li>
<li><code dir="ltr" translate="no">ml.trials.get</code></li>
<li><code dir="ltr" translate="no">ml.trials.list</code></li>
<li><code dir="ltr" translate="no">ml.trials.update</code></li>
<li><code dir="ltr" translate="no">ml.versions.create</code></li>
<li><code dir="ltr" translate="no">ml.versions.delete</code></li>
<li><code dir="ltr" translate="no">ml.versions.get</code></li>
<li><code dir="ltr" translate="no">ml.versions.list</code></li>
<li><code dir="ltr" translate="no">ml.versions.predict</code></li>
<li><code dir="ltr" translate="no">ml.versions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="ml.viewer" class="role-title add-link" data-text="AI Platform Viewer" tabindex="-1">AI Platform Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p>Provides read-only access to AI Platform resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.jobs.get</code></p>
<p><code dir="ltr" translate="no">ml.jobs.list</code></p>
<p><code dir="ltr" translate="no">ml.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.locations.get</code></li>
<li><code dir="ltr" translate="no">ml.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">ml.models.get</code></p>
<p><code dir="ltr" translate="no">ml.models.list</code></p>
<p><code dir="ltr" translate="no">ml.operations.get</code></p>
<p><code dir="ltr" translate="no">ml.operations.list</code></p>
<p><code dir="ltr" translate="no">ml.projects.getConfig</code></p>
<p><code dir="ltr" translate="no">ml.studies.get</code></p>
<p><code dir="ltr" translate="no">ml.studies.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.studies.list</code></p>
<p><code dir="ltr" translate="no">ml.trials.get</code></p>
<p><code dir="ltr" translate="no">ml.trials.list</code></p>
<p><code dir="ltr" translate="no">ml.versions.get</code></p>
<p><code dir="ltr" translate="no">ml.versions.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="ml.developer" class="role-title add-link" data-text="AI Platform Developer" tabindex="-1">AI Platform Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Provides ability to use AI Platform resources for creating models, versions, jobs for training and prediction, and sending online prediction requests.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.jobs.create</code></p>
<p><code dir="ltr" translate="no">ml.jobs.get</code></p>
<p><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.jobs.list</code></p>
<p><code dir="ltr" translate="no">ml.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.locations.get</code></li>
<li><code dir="ltr" translate="no">ml.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">ml.models.create</code></p>
<p><code dir="ltr" translate="no">ml.models.get</code></p>
<p><code dir="ltr" translate="no">ml.models.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.models.list</code></p>
<p><code dir="ltr" translate="no">ml.models.predict</code></p>
<p><code dir="ltr" translate="no">ml.operations.get</code></p>
<p><code dir="ltr" translate="no">ml.operations.list</code></p>
<p><code dir="ltr" translate="no">ml.projects.getConfig</code></p>
<p><code dir="ltr" translate="no">ml.studies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.studies.create</code></li>
<li><code dir="ltr" translate="no">ml.studies.delete</code></li>
<li><code dir="ltr" translate="no">ml.studies.get</code></li>
<li><code dir="ltr" translate="no">ml.studies.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.studies.list</code></li>
<li><code dir="ltr" translate="no">ml.studies.setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">ml.trials.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.trials.create</code></li>
<li><code dir="ltr" translate="no">ml.trials.delete</code></li>
<li><code dir="ltr" translate="no">ml.trials.get</code></li>
<li><code dir="ltr" translate="no">ml.trials.list</code></li>
<li><code dir="ltr" translate="no">ml.trials.update</code></li>
</ul>
<p><code dir="ltr" translate="no">ml.versions.get</code></p>
<p><code dir="ltr" translate="no">ml.versions.list</code></p>
<p><code dir="ltr" translate="no">ml.versions.predict</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="ml.jobOwner" class="role-title add-link" data-text="AI Platform Job Owner" tabindex="-1">AI Platform Job Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p>
<p>Provides full access to all permissions for a particular job resource. This role is automatically granted to the user who creates the job.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Job</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">ml.jobs.create</code></li>
<li><code dir="ltr" translate="no">ml.jobs.get</code></li>
<li><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.jobs.list</code></li>
<li><code dir="ltr" translate="no">ml.jobs.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.jobs.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.modelOwner" class="role-title add-link" data-text="AI Platform Model Owner" tabindex="-1">AI Platform Model Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Provides full access to the model and its versions. This role is automatically granted to the user who creates the model.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Model</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.models.create</code></li>
<li><code dir="ltr" translate="no">ml.models.delete</code></li>
<li><code dir="ltr" translate="no">ml.models.get</code></li>
<li><code dir="ltr" translate="no">ml.models.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.models.list</code></li>
<li><code dir="ltr" translate="no">ml.models.predict</code></li>
<li><code dir="ltr" translate="no">ml.models.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">ml.models.update</code></li>
</ul>
<p><code dir="ltr" translate="no">ml.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.versions.create</code></li>
<li><code dir="ltr" translate="no">ml.versions.delete</code></li>
<li><code dir="ltr" translate="no">ml.versions.get</code></li>
<li><code dir="ltr" translate="no">ml.versions.list</code></li>
<li><code dir="ltr" translate="no">ml.versions.predict</code></li>
<li><code dir="ltr" translate="no">ml.versions.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.modelUser" class="role-title add-link" data-text="AI Platform Model User" tabindex="-1">AI Platform Model User</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.modelUser</code> )</p>
<p>Provides permissions to read the model and its versions, and use them for prediction.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Model</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.models.get</code></p>
<p><code dir="ltr" translate="no">ml.models.predict</code></p>
<p><code dir="ltr" translate="no">ml.versions.get</code></p>
<p><code dir="ltr" translate="no">ml.versions.list</code></p>
<p><code dir="ltr" translate="no">ml.versions.predict</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="ml.operationOwner" class="role-title add-link" data-text="AI Platform Operation Owner" tabindex="-1">AI Platform Operation Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.operationOwner</code> )</p>
<p>Provides full access to all permissions for a particular operation resource.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Operation</li>
</ul></td>
<td><p><code dir="ltr" translate="no">ml.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.operations.cancel</code></li>
<li><code dir="ltr" translate="no">ml.operations.get</code></li>
<li><code dir="ltr" translate="no">ml.operations.list</code></li>
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
<td><h4 id="ml.serviceAgent" class="role-title add-link" data-text="AI Platform Service Agent" tabindex="-1">AI Platform Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</p>
<p>AI Platform service agent can act as log writer, Cloud Storage admin, Artifact Registry Reader, BigQuery writer, and service account access token creator.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  implicitDelegation</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signJwt</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.anywhereCaches.create</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.disable</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.get</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.list</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.pause</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.resume</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.bucketOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  bucketOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.get</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.buckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.buckets.create</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.buckets.delete</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  enableObjectRetention</code></li>
<li><code dir="ltr" translate="no">storage.buckets.get</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  getObjectInsights</code></li>
<li><code dir="ltr" translate="no">storage.buckets.list</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">storage.buckets.relocate</code></li>
<li><code dir="ltr" translate="no">storage.buckets.restore</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.buckets.update</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.featureConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.featureConfigs.create</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.delete</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.get</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.list</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.intelligenceConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></li>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.managedFolders.create</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.delete</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.get</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.list</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.multipartUploads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.multipartUploads.abort</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></li>
<li><code dir="ltr" translate="no">storage.multipartUploads.list</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.objects.create</code></li>
<li><code dir="ltr" translate="no">storage.objects.createContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.delete</code></li>
<li><code dir="ltr" translate="no">storage.objects.deleteContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.get</code></li>
<li><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.list</code></li>
<li><code dir="ltr" translate="no">storage.objects.move</code></li>
<li><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.restore</code></li>
<li><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.setRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.update</code></li>
<li><code dir="ltr" translate="no">storage.objects.updateContext</code></li>
</ul>
<p><code dir="ltr" translate="no">storagebatchoperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  create</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  list</code></li>
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
<td><h4 id="ml.jobs.cancel" class="permission-name add-link" data-text="ml.jobs.cancel" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ml.jobs.create" class="permission-name add-link" data-text="ml.jobs.create" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.jobs.get" class="permission-name add-link" data-text="ml.jobs.get" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.jobs.getIamPolicy" class="permission-name add-link" data-text="ml.jobs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.jobs.list" class="permission-name add-link" data-text="ml.jobs.list" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.jobs.setIamPolicy" class="permission-name add-link" data-text="ml.jobs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ml.jobs.update" class="permission-name add-link" data-text="ml.jobs.update" tabindex="-1"><code dir="ltr" translate="no">ml.jobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.jobOwner">AI Platform Job Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.jobOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ml.locations.get" class="permission-name add-link" data-text="ml.locations.get" tabindex="-1"><code dir="ltr" translate="no">ml.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.locations.list" class="permission-name add-link" data-text="ml.locations.list" tabindex="-1"><code dir="ltr" translate="no">ml.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.models.create" class="permission-name add-link" data-text="ml.models.create" tabindex="-1"><code dir="ltr" translate="no">ml.models.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.models.delete" class="permission-name add-link" data-text="ml.models.delete" tabindex="-1"><code dir="ltr" translate="no">ml.models.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.models.get" class="permission-name add-link" data-text="ml.models.get" tabindex="-1"><code dir="ltr" translate="no">ml.models.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.models.getIamPolicy" class="permission-name add-link" data-text="ml.models.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ml.models.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.models.list" class="permission-name add-link" data-text="ml.models.list" tabindex="-1"><code dir="ltr" translate="no">ml.models.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.models.predict" class="permission-name add-link" data-text="ml.models.predict" tabindex="-1"><code dir="ltr" translate="no">ml.models.predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.models.setIamPolicy" class="permission-name add-link" data-text="ml.models.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ml.models.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.models.update" class="permission-name add-link" data-text="ml.models.update" tabindex="-1"><code dir="ltr" translate="no">ml.models.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.operations.cancel" class="permission-name add-link" data-text="ml.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">ml.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.operationOwner">AI Platform Operation Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.operationOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ml.operations.get" class="permission-name add-link" data-text="ml.operations.get" tabindex="-1"><code dir="ltr" translate="no">ml.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.operationOwner">AI Platform Operation Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.operationOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.operations.list" class="permission-name add-link" data-text="ml.operations.list" tabindex="-1"><code dir="ltr" translate="no">ml.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.operationOwner">AI Platform Operation Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.operationOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.projects.getConfig" class="permission-name add-link" data-text="ml.projects.getConfig" tabindex="-1"><code dir="ltr" translate="no">ml.projects.getConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.studies.create" class="permission-name add-link" data-text="ml.studies.create" tabindex="-1"><code dir="ltr" translate="no">ml.studies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.studies.delete" class="permission-name add-link" data-text="ml.studies.delete" tabindex="-1"><code dir="ltr" translate="no">ml.studies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.studies.get" class="permission-name add-link" data-text="ml.studies.get" tabindex="-1"><code dir="ltr" translate="no">ml.studies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.studies.getIamPolicy" class="permission-name add-link" data-text="ml.studies.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ml.studies.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.studies.list" class="permission-name add-link" data-text="ml.studies.list" tabindex="-1"><code dir="ltr" translate="no">ml.studies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.studies.setIamPolicy" class="permission-name add-link" data-text="ml.studies.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ml.studies.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.trials.create" class="permission-name add-link" data-text="ml.trials.create" tabindex="-1"><code dir="ltr" translate="no">ml.trials.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.trials.delete" class="permission-name add-link" data-text="ml.trials.delete" tabindex="-1"><code dir="ltr" translate="no">ml.trials.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.trials.get" class="permission-name add-link" data-text="ml.trials.get" tabindex="-1"><code dir="ltr" translate="no">ml.trials.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.trials.list" class="permission-name add-link" data-text="ml.trials.list" tabindex="-1"><code dir="ltr" translate="no">ml.trials.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.trials.update" class="permission-name add-link" data-text="ml.trials.update" tabindex="-1"><code dir="ltr" translate="no">ml.trials.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.versions.create" class="permission-name add-link" data-text="ml.versions.create" tabindex="-1"><code dir="ltr" translate="no">ml.versions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.versions.delete" class="permission-name add-link" data-text="ml.versions.delete" tabindex="-1"><code dir="ltr" translate="no">ml.versions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.versions.get" class="permission-name add-link" data-text="ml.versions.get" tabindex="-1"><code dir="ltr" translate="no">ml.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.versions.list" class="permission-name add-link" data-text="ml.versions.list" tabindex="-1"><code dir="ltr" translate="no">ml.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="ml.versions.predict" class="permission-name add-link" data-text="ml.versions.predict" tabindex="-1"><code dir="ltr" translate="no">ml.versions.predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelUser">AI Platform Model User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="ml.versions.update" class="permission-name add-link" data-text="ml.versions.update" tabindex="-1"><code dir="ltr" translate="no">ml.versions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.modelOwner">AI Platform Model Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.modelOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
