---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions
title: Cloud Run functions roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Run functions. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Run functions roles

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
<td><h4 id="cloudfunctions.admin" class="role-title add-link" data-text="Cloud Functions Admin" tabindex="-1">Cloud Functions Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p>Full access to functions, operations and locations.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudfunctions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.functions.call</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  create</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  delete</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  generationUpgrade</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.functions.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.functions.list</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeGet</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeSet</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.  functions.  update</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.locations.list</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  create</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  delete</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  publish</code></li>
<li><code dir="ltr" translate="no">eventarc.  channelConnections.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.attach</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.create</code></li>
<li><code dir="ltr" translate="no">eventarc.  channels.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.  channels.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.get</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.list</code></li>
<li><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.publish</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.undelete</code></li>
<li><code dir="ltr" translate="no">eventarc.channels.update</code></li>
<li><code dir="ltr" translate="no">eventarc.enrollments.create</code></li>
<li><code dir="ltr" translate="no">eventarc.enrollments.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.enrollments.get</code></li>
<li><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.enrollments.list</code></li>
<li><code dir="ltr" translate="no">eventarc.  enrollments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.enrollments.update</code></li>
<li><code dir="ltr" translate="no">eventarc.  events.  receiveAuditLogWritten</code></li>
<li><code dir="ltr" translate="no">eventarc.events.receiveEvent</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleApiSources.  create</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleApiSources.  delete</code></li>
<li><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleApiSources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleApiSources.  update</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  update</code></li>
<li><code dir="ltr" translate="no">eventarc.kafkaSources.create</code></li>
<li><code dir="ltr" translate="no">eventarc.kafkaSources.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></li>
<li><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></li>
<li><code dir="ltr" translate="no">eventarc.  kafkaSources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.create</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.get</code></li>
<li><code dir="ltr" translate="no">eventarc.  messageBuses.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.list</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.publish</code></li>
<li><code dir="ltr" translate="no">eventarc.  messageBuses.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.update</code></li>
<li><code dir="ltr" translate="no">eventarc.messageBuses.use</code></li>
<li><code dir="ltr" translate="no">eventarc.  multiProjectSources.  collectGoogleApiEvents</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.cancel</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.list</code></li>
<li><code dir="ltr" translate="no">eventarc.pipelines.create</code></li>
<li><code dir="ltr" translate="no">eventarc.pipelines.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.pipelines.get</code></li>
<li><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.pipelines.list</code></li>
<li><code dir="ltr" translate="no">eventarc.  pipelines.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.pipelines.update</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.create</code></li>
<li><code dir="ltr" translate="no">eventarc.  triggers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.  triggers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.list</code></li>
<li><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.undelete</code></li>
<li><code dir="ltr" translate="no">eventarc.triggers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
<li><code dir="ltr" translate="no">run.jobs.create</code></li>
<li><code dir="ltr" translate="no">run.jobs.createTagBinding</code></li>
<li><code dir="ltr" translate="no">run.jobs.delete</code></li>
<li><code dir="ltr" translate="no">run.jobs.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">run.jobs.get</code></li>
<li><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.jobs.list</code></li>
<li><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">run.jobs.listTagBindings</code></li>
<li><code dir="ltr" translate="no">run.jobs.run</code></li>
<li><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></li>
<li><code dir="ltr" translate="no">run.jobs.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.jobs.update</code></li>
<li><code dir="ltr" translate="no">run.locations.list</code></li>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
<li><code dir="ltr" translate="no">run.prompts.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
<li><code dir="ltr" translate="no">run.services.create</code></li>
<li><code dir="ltr" translate="no">run.services.createTagBinding</code></li>
<li><code dir="ltr" translate="no">run.services.delete</code></li>
<li><code dir="ltr" translate="no">run.services.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">run.services.get</code></li>
<li><code dir="ltr" translate="no">run.services.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.services.list</code></li>
<li><code dir="ltr" translate="no">run.services.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">run.services.listTagBindings</code></li>
<li><code dir="ltr" translate="no">run.services.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.services.update</code></li>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
<li><code dir="ltr" translate="no">run.workerpools.create</code></li>
<li><code dir="ltr" translate="no">run.workerpools.delete</code></li>
<li><code dir="ltr" translate="no">run.workerpools.get</code></li>
<li><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.workerpools.list</code></li>
<li><code dir="ltr" translate="no">run.workerpools.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.workerpools.update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.editor" class="role-title add-link" data-text="Cloud Functions Editor" tabindex="-1">Cloud Functions Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p>Editor role for Cloud Functions</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudfunctions.functions.call</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  create</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  delete</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  generationUpgrade</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeGet</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeSet</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  update</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.attach</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.create</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.update</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.create</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.create</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.messageBuses.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  messageBuses.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.list</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.use</code></p>
<p><code dir="ltr" translate="no">eventarc.  multiProjectSources.  collectGoogleApiEvents</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.operations.cancel</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.pipelines.create</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.update</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.triggers.create</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.get</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.update</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.jobs.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.delete</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p>
<p><code dir="ltr" translate="no">run.jobs.update</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.services.create</code></p>
<p><code dir="ltr" translate="no">run.services.delete</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.update</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.create</code></p>
<p><code dir="ltr" translate="no">run.workerpools.delete</code></p>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.update</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.invoker" class="role-title add-link" data-text="Cloud Functions Invoker" tabindex="-1">Cloud Functions Invoker</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudfunctions.invoker</code> )</p>
<p>Ability to invoke 1st gen HTTP functions with restricted access. 2nd gen functions need the Cloud Run Invoker role instead.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
<td><p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.viewer" class="role-title add-link" data-text="Cloud Functions Viewer" tabindex="-1">Cloud Functions Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p>Read-only access to functions and locations.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.messageBuses.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  messageBuses.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.list</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.use</code></p>
<p><code dir="ltr" translate="no">eventarc.  multiProjectSources.  collectGoogleApiEvents</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.get</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.list</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.triggers.get</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.get</code></p>
<p><code dir="ltr" translate="no">run.executions.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.get</code></p>
<p><code dir="ltr" translate="no">run.operations.list</code></p>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.list</code></p>
<p><code dir="ltr" translate="no">run.routes.get</code></p>
<p><code dir="ltr" translate="no">run.routes.list</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.developer" class="role-title add-link" data-text="Cloud Functions Developer" tabindex="-1">Cloud Functions Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p>Read and write access to all functions-related resources.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudfunctions.functions.call</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  create</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  delete</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  generationUpgrade</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeGet</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeSet</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  update</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.attach</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.create</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.update</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.create</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.create</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.operations.cancel</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.pipelines.create</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.update</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.triggers.create</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.get</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.update</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.jobs.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.delete</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p>
<p><code dir="ltr" translate="no">run.jobs.update</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.services.create</code></p>
<p><code dir="ltr" translate="no">run.services.delete</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.update</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.create</code></p>
<p><code dir="ltr" translate="no">run.workerpools.delete</code></p>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.update</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
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
<td><h4 id="cloudfunctions.serviceAgent" class="role-title add-link" data-text="Cloud Functions Service Agent" tabindex="-1">Cloud Functions Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</p>
<p>Gives Cloud Functions service account access to managed resources.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.files.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.files.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  files.  download</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.upload</code></li>
</ul>
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
<p><code dir="ltr" translate="no">artifactregistry.packages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.rules.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.tags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.workerpools.use</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.access</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.attach</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.create</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.update</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.create</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.create</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.operations.cancel</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.pipelines.create</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.update</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.triggers.create</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.get</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.update</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.instances.get</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.  instances.  update</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.jobs.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.delete</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p>
<p><code dir="ltr" translate="no">run.jobs.update</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.services.create</code></p>
<p><code dir="ltr" translate="no">run.services.delete</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.update</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.create</code></p>
<p><code dir="ltr" translate="no">run.workerpools.delete</code></p>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.update</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">source.repos.get</code></p>
<p><code dir="ltr" translate="no">source.repos.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.get</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.use</code></p></td>
</tr>
</tbody>
</table>

## Cloud Run functions permissions

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
<td><h4 id="cloudfunctions.functions.call" class="permission-name add-link" data-text="cloudfunctions.functions.call" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.functions.call</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.functions.create" class="permission-name add-link" data-text="cloudfunctions.functions.create" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.functions.delete" class="permission-name add-link" data-text="cloudfunctions.functions.delete" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.functions.generationUpgrade" class="permission-name add-link" data-text="cloudfunctions.functions.generationUpgrade" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  generationUpgrade</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.functions.get" class="permission-name add-link" data-text="cloudfunctions.functions.get" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.functions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.functions.getIamPolicy" class="permission-name add-link" data-text="cloudfunctions.functions.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.functions.invoke" class="permission-name add-link" data-text="cloudfunctions.functions.invoke" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.invoker">Cloud Functions Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.functions.list" class="permission-name add-link" data-text="cloudfunctions.functions.list" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.functions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.functions.setIamPolicy" class="permission-name add-link" data-text="cloudfunctions.functions.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.functions.sourceCodeGet" class="permission-name add-link" data-text="cloudfunctions.functions.sourceCodeGet" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeGet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.functions.sourceCodeSet" class="permission-name add-link" data-text="cloudfunctions.functions.sourceCodeSet" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  sourceCodeSet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.functions.update" class="permission-name add-link" data-text="cloudfunctions.functions.update" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.  functions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.locations.list" class="permission-name add-link" data-text="cloudfunctions.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudfunctions.operations.get" class="permission-name add-link" data-text="cloudfunctions.operations.get" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudfunctions.operations.list" class="permission-name add-link" data-text="cloudfunctions.operations.list" tabindex="-1"><code dir="ltr" translate="no">cloudfunctions.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
