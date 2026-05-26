---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebase
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebase
title: Firebase roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase roles

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
<td><h4 id="firebase.admin" class="role-title add-link" data-text="Firebase Admin" tabindex="-1">Firebase Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p>Full access to Firebase products.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.getKeyString</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.lookup</code></p>
<p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
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
<p><code dir="ltr" translate="no">automl.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.annotationSpecs.create</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.delete</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.update</code></li>
<li><code dir="ltr" translate="no">automl.annotations.approve</code></li>
<li><code dir="ltr" translate="no">automl.annotations.create</code></li>
<li><code dir="ltr" translate="no">automl.annotations.list</code></li>
<li><code dir="ltr" translate="no">automl.annotations.manipulate</code></li>
<li><code dir="ltr" translate="no">automl.annotations.reject</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.update</code></li>
<li><code dir="ltr" translate="no">automl.datasets.create</code></li>
<li><code dir="ltr" translate="no">automl.datasets.delete</code></li>
<li><code dir="ltr" translate="no">automl.datasets.export</code></li>
<li><code dir="ltr" translate="no">automl.datasets.get</code></li>
<li><code dir="ltr" translate="no">automl.datasets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.datasets.import</code></li>
<li><code dir="ltr" translate="no">automl.datasets.list</code></li>
<li><code dir="ltr" translate="no">automl.datasets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.datasets.update</code></li>
<li><code dir="ltr" translate="no">automl.examples.delete</code></li>
<li><code dir="ltr" translate="no">automl.examples.get</code></li>
<li><code dir="ltr" translate="no">automl.examples.list</code></li>
<li><code dir="ltr" translate="no">automl.examples.update</code></li>
<li><code dir="ltr" translate="no">automl.files.delete</code></li>
<li><code dir="ltr" translate="no">automl.files.list</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  create</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  delete</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></li>
<li><code dir="ltr" translate="no">automl.locations.get</code></li>
<li><code dir="ltr" translate="no">automl.locations.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.locations.list</code></li>
<li><code dir="ltr" translate="no">automl.locations.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.create</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.get</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.list</code></li>
<li><code dir="ltr" translate="no">automl.models.create</code></li>
<li><code dir="ltr" translate="no">automl.models.delete</code></li>
<li><code dir="ltr" translate="no">automl.models.deploy</code></li>
<li><code dir="ltr" translate="no">automl.models.export</code></li>
<li><code dir="ltr" translate="no">automl.models.get</code></li>
<li><code dir="ltr" translate="no">automl.models.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.models.list</code></li>
<li><code dir="ltr" translate="no">automl.models.predict</code></li>
<li><code dir="ltr" translate="no">automl.models.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.models.undeploy</code></li>
<li><code dir="ltr" translate="no">automl.operations.cancel</code></li>
<li><code dir="ltr" translate="no">automl.operations.delete</code></li>
<li><code dir="ltr" translate="no">automl.operations.get</code></li>
<li><code dir="ltr" translate="no">automl.operations.list</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.update</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  create</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  delete</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  update</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
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
<p><code dir="ltr" translate="no">cloudconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudconfig.configs.get</code></li>
<li><code dir="ltr" translate="no">cloudconfig.configs.update</code></li>
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
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">cloudmessaging.messages.create</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.matrices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtoolresults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  update</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  histories.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.histories.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  settings.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.settings.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  settings.  update</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.update</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  list</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></li>
<li><code dir="ltr" translate="no">datastore.backups.delete</code></li>
<li><code dir="ltr" translate="no">datastore.backups.get</code></li>
<li><code dir="ltr" translate="no">datastore.backups.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backups.  restoreDatabase</code></li>
<li><code dir="ltr" translate="no">datastore.databases.bulkDelete</code></li>
<li><code dir="ltr" translate="no">datastore.databases.clone</code></li>
<li><code dir="ltr" translate="no">datastore.databases.create</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.delete</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.export</code></li>
<li><code dir="ltr" translate="no">datastore.databases.get</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></li>
<li><code dir="ltr" translate="no">datastore.databases.import</code></li>
<li><code dir="ltr" translate="no">datastore.databases.list</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastore.databases.update</code></li>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
<li><code dir="ltr" translate="no">datastore.insights.get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></li>
<li><code dir="ltr" translate="no">datastore.locations.get</code></li>
<li><code dir="ltr" translate="no">datastore.locations.list</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
<li><code dir="ltr" translate="no">datastore.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datastore.operations.delete</code></li>
<li><code dir="ltr" translate="no">datastore.operations.get</code></li>
<li><code dir="ltr" translate="no">datastore.operations.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.create</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.delete</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.get</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.update</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.create</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.delete</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.get</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
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
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">firebase.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebase.billingPlans.get</code></li>
<li><code dir="ltr" translate="no">firebase.billingPlans.update</code></li>
<li><code dir="ltr" translate="no">firebase.clients.create</code></li>
<li><code dir="ltr" translate="no">firebase.clients.delete</code></li>
<li><code dir="ltr" translate="no">firebase.clients.get</code></li>
<li><code dir="ltr" translate="no">firebase.clients.list</code></li>
<li><code dir="ltr" translate="no">firebase.clients.undelete</code></li>
<li><code dir="ltr" translate="no">firebase.clients.update</code></li>
<li><code dir="ltr" translate="no">firebase.links.create</code></li>
<li><code dir="ltr" translate="no">firebase.links.delete</code></li>
<li><code dir="ltr" translate="no">firebase.links.list</code></li>
<li><code dir="ltr" translate="no">firebase.links.update</code></li>
<li><code dir="ltr" translate="no">firebase.playLinks.get</code></li>
<li><code dir="ltr" translate="no">firebase.playLinks.list</code></li>
<li><code dir="ltr" translate="no">firebase.playLinks.update</code></li>
<li><code dir="ltr" translate="no">firebase.projects.delete</code></li>
<li><code dir="ltr" translate="no">firebase.projects.get</code></li>
<li><code dir="ltr" translate="no">firebase.projects.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseabt.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.create</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.delete</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.list</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.update</code></li>
<li><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></li>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseappcheck.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  appCheckTokens.  verify</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  create</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  resume</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  suspend</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.services.get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseappdistro.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  groups.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  testers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  builds.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  builds.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.builds.get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  builds.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.domains.get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.traffic.get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  traffic.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseauth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.configs.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.update</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasecrash.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasecrash.issues.update</code></li>
<li><code dir="ltr" translate="no">firebasecrash.reports.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasecrashlytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasecrashlytics.config.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  config.  update</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.data.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.issues.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  issues.  update</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  sessions.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedatabase.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  create</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  disable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.instances.get</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  reenable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  undelete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  impersonateMutation</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  impersonateQuery</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  update</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  update</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  executeGraphql</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  executeGraphqlRead</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  introspectGraphql</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedynamiclinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseextensions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseextensions.  configs.  create</code></li>
<li><code dir="ltr" translate="no">firebaseextensions.  configs.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></li>
<li><code dir="ltr" translate="no">firebaseextensions.  configs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasehosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasehosting.sites.create</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.delete</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.get</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.list</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseinappmessaging.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  create</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  get</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  create</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  delete</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  get</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  start</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  stop</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseml.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseml.models.create</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.delete</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.update</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasenotifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  create</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  delete</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  get</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseperformance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseperformance.  config.  update</code></li>
<li><code dir="ltr" translate="no">firebaseperformance.data.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaserules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaserules.releases.create</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.delete</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.get</code></li>
<li><code dir="ltr" translate="no">firebaserules.  releases.  getExecutable</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.list</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.update</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.create</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.delete</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.get</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.list</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.test</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasestorage.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasestorage.  buckets.  addFirebase</code></li>
<li><code dir="ltr" translate="no">firebasestorage.buckets.get</code></li>
<li><code dir="ltr" translate="no">firebasestorage.buckets.list</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  buckets.  removeFirebase</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  create</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  delete</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasevertexai.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasevertexai.configs.get</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  configs.  update</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  create</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  get</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  update</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  updateLock</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
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
<p><code dir="ltr" translate="no">runtimeconfig.configs.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runtimeconfig.operations.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runtimeconfig.variables.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.watch</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.update</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
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
<tr class="even">
<td><h4 id="firebase.editor" class="role-title add-link" data-text="Firebase Editor" tabindex="-1">Firebase Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p>Editor access to Firebase products.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.annotations.list</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.get</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.examples.get</code></p>
<p><code dir="ltr" translate="no">automl.examples.list</code></p>
<p><code dir="ltr" translate="no">automl.files.list</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></p>
<p><code dir="ltr" translate="no">automl.locations.get</code></p>
<p><code dir="ltr" translate="no">automl.locations.list</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.get</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.list</code></p>
<p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.operations.get</code></p>
<p><code dir="ltr" translate="no">automl.operations.list</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
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
<p><code dir="ltr" translate="no">cloudconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudconfig.configs.get</code></li>
<li><code dir="ltr" translate="no">cloudconfig.configs.update</code></li>
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
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  update</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  use</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtoolresults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  update</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  histories.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.histories.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  settings.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.settings.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  settings.  update</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.get</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.get</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.userCreds.get</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.list</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
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
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebase.clients.create</code></li>
<li><code dir="ltr" translate="no">firebase.clients.delete</code></li>
<li><code dir="ltr" translate="no">firebase.clients.get</code></li>
<li><code dir="ltr" translate="no">firebase.clients.list</code></li>
<li><code dir="ltr" translate="no">firebase.clients.undelete</code></li>
<li><code dir="ltr" translate="no">firebase.clients.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebase.projects.update</code></p>
<p><code dir="ltr" translate="no">firebaseabt.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.create</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.delete</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.list</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.update</code></li>
<li><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></li>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.services.get</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  groups.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  testers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.domains.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.traffic.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.configs.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.update</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasecrash.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasecrash.issues.update</code></li>
<li><code dir="ltr" translate="no">firebasecrash.reports.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasecrashlytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasecrashlytics.config.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  config.  update</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.data.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.issues.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  issues.  update</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  sessions.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedatabase.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  create</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  disable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.instances.get</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  reenable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  undelete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  introspectGraphql</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  create</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  update</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasehosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasehosting.sites.create</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.delete</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.get</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.list</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseinappmessaging.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  create</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  get</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  get</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebaseml.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseml.models.create</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.delete</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.update</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasenotifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  create</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  delete</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  get</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseperformance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseperformance.  config.  update</code></li>
<li><code dir="ltr" translate="no">firebaseperformance.data.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaserules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaserules.releases.create</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.delete</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.get</code></li>
<li><code dir="ltr" translate="no">firebaserules.  releases.  getExecutable</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.list</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.update</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.create</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.delete</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.get</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.list</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.test</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasestorage.buckets.get</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.configs.get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.viewer" class="role-title add-link" data-text="Firebase Viewer" tabindex="-1">Firebase Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p>Read-only access to Firebase products.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.annotations.list</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.get</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.examples.get</code></p>
<p><code dir="ltr" translate="no">automl.examples.list</code></p>
<p><code dir="ltr" translate="no">automl.files.list</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></p>
<p><code dir="ltr" translate="no">automl.locations.get</code></p>
<p><code dir="ltr" translate="no">automl.locations.list</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.get</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.list</code></p>
<p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.operations.get</code></p>
<p><code dir="ltr" translate="no">automl.operations.list</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
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
<p><code dir="ltr" translate="no">cloudconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  executions.  get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.histories.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.settings.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.steps.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></p>
<p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.get</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.get</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.userCreds.get</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.list</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
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
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.list</code></p>
<p><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.services.get</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.domains.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.traffic.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.users.get</code></p>
<p><code dir="ltr" translate="no">firebasecrash.reports.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.config.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.data.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.issues.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.  sessions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.instances.get</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  introspectGraphql</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.get</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.list</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  get</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  get</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebaseml.models.get</code></p>
<p><code dir="ltr" translate="no">firebaseml.models.list</code></p>
<p><code dir="ltr" translate="no">firebaseml.modelversions.get</code></p>
<p><code dir="ltr" translate="no">firebaseml.modelversions.list</code></p>
<p><code dir="ltr" translate="no">firebasenotifications.  messages.  get</code></p>
<p><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></p>
<p><code dir="ltr" translate="no">firebaseperformance.data.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.get</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.configs.get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.analyticsAdmin" class="role-title add-link" data-text="Firebase Analytics Admin" tabindex="-1">Firebase Analytics Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p>Full access to Google Analytics for Firebase.</p></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></li>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.analyticsViewer" class="role-title add-link" data-text="Firebase Analytics Viewer" tabindex="-1">Firebase Analytics Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p>Read access to Google Analytics for Firebase.</p></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.developAdmin" class="role-title add-link" data-text="Firebase Develop Admin" tabindex="-1">Firebase Develop Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Full access to Firebase Develop products and Analytics.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.getKeyString</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.lookup</code></p>
<p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
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
<p><code dir="ltr" translate="no">automl.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.annotationSpecs.create</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.delete</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.update</code></li>
<li><code dir="ltr" translate="no">automl.annotations.approve</code></li>
<li><code dir="ltr" translate="no">automl.annotations.create</code></li>
<li><code dir="ltr" translate="no">automl.annotations.list</code></li>
<li><code dir="ltr" translate="no">automl.annotations.manipulate</code></li>
<li><code dir="ltr" translate="no">automl.annotations.reject</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.update</code></li>
<li><code dir="ltr" translate="no">automl.datasets.create</code></li>
<li><code dir="ltr" translate="no">automl.datasets.delete</code></li>
<li><code dir="ltr" translate="no">automl.datasets.export</code></li>
<li><code dir="ltr" translate="no">automl.datasets.get</code></li>
<li><code dir="ltr" translate="no">automl.datasets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.datasets.import</code></li>
<li><code dir="ltr" translate="no">automl.datasets.list</code></li>
<li><code dir="ltr" translate="no">automl.datasets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.datasets.update</code></li>
<li><code dir="ltr" translate="no">automl.examples.delete</code></li>
<li><code dir="ltr" translate="no">automl.examples.get</code></li>
<li><code dir="ltr" translate="no">automl.examples.list</code></li>
<li><code dir="ltr" translate="no">automl.examples.update</code></li>
<li><code dir="ltr" translate="no">automl.files.delete</code></li>
<li><code dir="ltr" translate="no">automl.files.list</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  create</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  delete</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></li>
<li><code dir="ltr" translate="no">automl.locations.get</code></li>
<li><code dir="ltr" translate="no">automl.locations.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.locations.list</code></li>
<li><code dir="ltr" translate="no">automl.locations.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.create</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.get</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.list</code></li>
<li><code dir="ltr" translate="no">automl.models.create</code></li>
<li><code dir="ltr" translate="no">automl.models.delete</code></li>
<li><code dir="ltr" translate="no">automl.models.deploy</code></li>
<li><code dir="ltr" translate="no">automl.models.export</code></li>
<li><code dir="ltr" translate="no">automl.models.get</code></li>
<li><code dir="ltr" translate="no">automl.models.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.models.list</code></li>
<li><code dir="ltr" translate="no">automl.models.predict</code></li>
<li><code dir="ltr" translate="no">automl.models.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">automl.models.undeploy</code></li>
<li><code dir="ltr" translate="no">automl.operations.cancel</code></li>
<li><code dir="ltr" translate="no">automl.operations.delete</code></li>
<li><code dir="ltr" translate="no">automl.operations.get</code></li>
<li><code dir="ltr" translate="no">automl.operations.list</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.update</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
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
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  list</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></li>
<li><code dir="ltr" translate="no">datastore.backups.delete</code></li>
<li><code dir="ltr" translate="no">datastore.backups.get</code></li>
<li><code dir="ltr" translate="no">datastore.backups.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backups.  restoreDatabase</code></li>
<li><code dir="ltr" translate="no">datastore.databases.bulkDelete</code></li>
<li><code dir="ltr" translate="no">datastore.databases.clone</code></li>
<li><code dir="ltr" translate="no">datastore.databases.create</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.delete</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.export</code></li>
<li><code dir="ltr" translate="no">datastore.databases.get</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></li>
<li><code dir="ltr" translate="no">datastore.databases.import</code></li>
<li><code dir="ltr" translate="no">datastore.databases.list</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastore.databases.update</code></li>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
<li><code dir="ltr" translate="no">datastore.insights.get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></li>
<li><code dir="ltr" translate="no">datastore.locations.get</code></li>
<li><code dir="ltr" translate="no">datastore.locations.list</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
<li><code dir="ltr" translate="no">datastore.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datastore.operations.delete</code></li>
<li><code dir="ltr" translate="no">datastore.operations.get</code></li>
<li><code dir="ltr" translate="no">datastore.operations.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.create</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.delete</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.get</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.update</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.create</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.delete</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.get</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
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
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></li>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseappcheck.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  appCheckTokens.  verify</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  create</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  resume</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  suspend</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.services.get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  backends.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  builds.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  builds.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.builds.get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  builds.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.domains.get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  domains.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  create</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  update</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.traffic.get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  traffic.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseauth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.configs.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.update</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedatabase.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  create</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  disable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.instances.get</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  reenable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  undelete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  impersonateMutation</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  impersonateQuery</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  update</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  update</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  executeGraphql</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  executeGraphqlRead</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  introspectGraphql</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasehosting.sites.create</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.delete</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.get</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.list</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseml.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseml.models.create</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.delete</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.update</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaserules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaserules.releases.create</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.delete</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.get</code></li>
<li><code dir="ltr" translate="no">firebaserules.  releases.  getExecutable</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.list</code></li>
<li><code dir="ltr" translate="no">firebaserules.releases.update</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.create</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.delete</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.get</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.list</code></li>
<li><code dir="ltr" translate="no">firebaserules.rulesets.test</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasestorage.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasestorage.  buckets.  addFirebase</code></li>
<li><code dir="ltr" translate="no">firebasestorage.buckets.get</code></li>
<li><code dir="ltr" translate="no">firebasestorage.buckets.list</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  buckets.  removeFirebase</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  create</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  delete</code></li>
<li><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasevertexai.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasevertexai.configs.get</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  configs.  update</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  create</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  get</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  update</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  updateLock</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
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
<p><code dir="ltr" translate="no">runtimeconfig.configs.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runtimeconfig.operations.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runtimeconfig.variables.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.watch</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.update</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
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
<tr class="odd">
<td><h4 id="firebase.developViewer" class="role-title add-link" data-text="Firebase Develop Viewer" tabindex="-1">Firebase Develop Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p>Read access to Firebase Develop products and Analytics.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.annotations.list</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.get</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.examples.get</code></p>
<p><code dir="ltr" translate="no">automl.examples.list</code></p>
<p><code dir="ltr" translate="no">automl.files.list</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></p>
<p><code dir="ltr" translate="no">automl.locations.get</code></p>
<p><code dir="ltr" translate="no">automl.locations.list</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.get</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.list</code></p>
<p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.operations.get</code></p>
<p><code dir="ltr" translate="no">automl.operations.list</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.get</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
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
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudfunctions.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudfunctions.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.get</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.get</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.userCreds.get</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.list</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
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
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  get</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.services.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.domains.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.traffic.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.users.get</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.instances.get</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  introspectGraphql</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.get</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.list</code></p>
<p><code dir="ltr" translate="no">firebaseml.models.get</code></p>
<p><code dir="ltr" translate="no">firebaseml.models.list</code></p>
<p><code dir="ltr" translate="no">firebaseml.modelversions.get</code></p>
<p><code dir="ltr" translate="no">firebaseml.modelversions.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.get</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.configs.get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.growthAdmin" class="role-title add-link" data-text="Firebase Grow Admin" tabindex="-1">Firebase Grow Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p>Full access to Firebase Grow products and Analytics.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloudconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudconfig.configs.get</code></li>
<li><code dir="ltr" translate="no">cloudconfig.configs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudmessaging.messages.create</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.create</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.delete</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.list</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.update</code></li>
<li><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></li>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedynamiclinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  create</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  get</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></li>
<li><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  create</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  delete</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  get</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  start</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  stop</code></li>
<li><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasenotifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  create</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  delete</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  get</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.growthViewer" class="role-title add-link" data-text="Firebase Grow Viewer" tabindex="-1">Firebase Grow Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p>Read access to Firebase Grow products and Analytics.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">cloudconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.list</code></p>
<p><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  get</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  get</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebasenotifications.  messages.  get</code></p>
<p><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.qualityAdmin" class="role-title add-link" data-text="Firebase Quality Admin" tabindex="-1">Firebase Quality Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p>Full access to Firebase Quality products and Analytics.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsEdit</code></li>
<li><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseappdistro.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  groups.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  testers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasecrash.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasecrash.issues.update</code></li>
<li><code dir="ltr" translate="no">firebasecrash.reports.get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasecrashlytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasecrashlytics.config.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  config.  update</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.data.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.issues.get</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  issues.  update</code></li>
<li><code dir="ltr" translate="no">firebasecrashlytics.  sessions.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseperformance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseperformance.  config.  update</code></li>
<li><code dir="ltr" translate="no">firebaseperformance.data.get</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.qualityViewer" class="role-title add-link" data-text="Firebase Quality Viewer" tabindex="-1">Firebase Quality Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p>Read access to Firebase Quality products and Analytics.</p></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.get</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseanalytics.  resources.  googleAnalyticsReadAndAnalyze</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></p>
<p><code dir="ltr" translate="no">firebasecrash.reports.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.config.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.data.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.issues.get</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.  sessions.  get</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseperformance.data.get</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
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
<td><h4 id="firebase.appDistributionSdkServiceAgent" class="role-title add-link" data-text="Firebase App Distribution Admin SDK Service Agent" tabindex="-1">Firebase App Distribution Admin SDK Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.appDistributionSdkServiceAgent</code> )</p>
<p>Read and write access to Firebase App Distribution with the Admin SDK</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">firebaseappdistro.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  groups.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  releases.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></li>
<li><code dir="ltr" translate="no">firebaseappdistro.  testers.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebase.managementServiceAgent" class="role-title add-link" data-text="Firebase Service Management Service Agent" tabindex="-1">Firebase Service Management Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</p>
<p>Access to create new service agents for Firebase projects; assign roles to service agents; provision GCP resources as required by Firebase services.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.create</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.get</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.getKeyString</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.update</code></p>
<p><code dir="ltr" translate="no">appengine.applications.create</code></p>
<p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">appengine.applications.update</code></p>
<p><code dir="ltr" translate="no">appengine.operations.get</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.update</code></p>
<p><code dir="ltr" translate="no">bigquery.transfers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.transfers.get</code></li>
<li><code dir="ltr" translate="no">bigquery.transfers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">clientauthconfig.brands.create</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.update</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  create</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  delete</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  getWithSecret</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  update</code></p>
<p><code dir="ltr" translate="no">datastore.databases.create</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.update</code></p>
<p><code dir="ltr" translate="no">datastore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.locations.get</code></li>
<li><code dir="ltr" translate="no">datastore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">firebase.clients.create</code></p>
<p><code dir="ltr" translate="no">firebase.clients.delete</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.undelete</code></p>
<p><code dir="ltr" translate="no">firebase.clients.update</code></p>
<p><code dir="ltr" translate="no">firebase.projects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebase.projects.delete</code></li>
<li><code dir="ltr" translate="no">firebase.projects.get</code></li>
<li><code dir="ltr" translate="no">firebase.projects.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseabt.experiments.delete</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseappcheck.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappcheck.services.get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  create</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.domains.get</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  update</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.create</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.update</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  create</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.create</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.get</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.update</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.create</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.delete</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.update</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.create</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.  defaultBucket.  get</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.configs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasevertexai.configs.get</code></li>
<li><code dir="ltr" translate="no">firebasevertexai.  configs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  create</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  update</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.bucketOperations.get</code></p>
<p><code dir="ltr" translate="no">storage.bucketOperations.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.sdkAdminServiceAgent" class="role-title add-link" data-text="Firebase Admin SDK Administrator Service Agent" tabindex="-1">Firebase Admin SDK Administrator Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</p>
<p>Read and write access to Firebase products available in the Admin SDK</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">cloudconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudconfig.configs.get</code></li>
<li><code dir="ltr" translate="no">cloudconfig.configs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudmessaging.messages.create</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.insights.get</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.get</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebase.clients.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebase.clients.create</code></li>
<li><code dir="ltr" translate="no">firebase.clients.delete</code></li>
<li><code dir="ltr" translate="no">firebase.clients.get</code></li>
<li><code dir="ltr" translate="no">firebase.clients.list</code></li>
<li><code dir="ltr" translate="no">firebase.clients.undelete</code></li>
<li><code dir="ltr" translate="no">firebase.clients.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebase.projects.update</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  appAttestConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  appCheckTokens.  verify</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  create</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  resume</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  suspend</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  automations.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  debugTokens.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  deviceCheckConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  playIntegrityConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaEnterpriseConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  recaptchaV3Config.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  safetyNetConfig.  update</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.services.get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseauth.configs.create</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.update</code></p>
<p><code dir="ltr" translate="no">firebaseauth.users.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedatabase.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  create</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  disable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.instances.get</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  reenable</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  undelete</code></li>
<li><code dir="ltr" translate="no">firebasedatabase.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedataconnect.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  impersonateMutation</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  impersonateQuery</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  connectors.  update</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  schemas.  update</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  create</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  executeGraphql</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  executeGraphqlRead</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  get</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  introspectGraphql</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></li>
<li><code dir="ltr" translate="no">firebasedataconnect.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasehosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasehosting.sites.create</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.delete</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.get</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.list</code></li>
<li><code dir="ltr" translate="no">firebasehosting.sites.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaseml.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseml.models.create</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.delete</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.models.update</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.get</code></li>
<li><code dir="ltr" translate="no">firebaseml.modelversions.list</code></li>
<li><code dir="ltr" translate="no">firebaseml.  modelversions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasenotifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  create</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  delete</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  get</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></li>
<li><code dir="ltr" translate="no">firebasenotifications.  messages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebaserules.releases.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.update</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.create</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.delete</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.get</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.list</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.*</code></p>
<ul>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.create</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.delete</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.  tenants.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  update</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.create</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.delete</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
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
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebase.sdkProvisioningServiceAgent" class="role-title add-link" data-text="Firebase SDK Provisioning Service Agent" tabindex="-1">Firebase SDK Provisioning Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  firebase.sdkProvisioningServiceAgent</code> )</p>
<p>Access to provision apps with the Admin SDK.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloudmessaging.messages.create</code></p>
<p><code dir="ltr" translate="no">firebase.clients.create</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Firebase permissions

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
<td><h4 id="firebase.billingPlans.get" class="permission-name add-link" data-text="firebase.billingPlans.get" tabindex="-1"><code dir="ltr" translate="no">firebase.billingPlans.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.billingPlans.update" class="permission-name add-link" data-text="firebase.billingPlans.update" tabindex="-1"><code dir="ltr" translate="no">firebase.billingPlans.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.clients.create" class="permission-name add-link" data-text="firebase.clients.create" tabindex="-1"><code dir="ltr" translate="no">firebase.clients.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkProvisioningServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebase.clients.delete" class="permission-name add-link" data-text="firebase.clients.delete" tabindex="-1"><code dir="ltr" translate="no">firebase.clients.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.clients.get" class="permission-name add-link" data-text="firebase.clients.get" tabindex="-1"><code dir="ltr" translate="no">firebase.clients.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrash.symbolMappingsAdmin">Firebase Crash Symbol Uploader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrash.symbolMappingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebase.clients.list" class="permission-name add-link" data-text="firebase.clients.list" tabindex="-1"><code dir="ltr" translate="no">firebase.clients.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrash.symbolMappingsAdmin">Firebase Crash Symbol Uploader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrash.symbolMappingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.clients.undelete" class="permission-name add-link" data-text="firebase.clients.undelete" tabindex="-1"><code dir="ltr" translate="no">firebase.clients.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebase.clients.update" class="permission-name add-link" data-text="firebase.clients.update" tabindex="-1"><code dir="ltr" translate="no">firebase.clients.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.links.create" class="permission-name add-link" data-text="firebase.links.create" tabindex="-1"><code dir="ltr" translate="no">firebase.links.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.links.delete" class="permission-name add-link" data-text="firebase.links.delete" tabindex="-1"><code dir="ltr" translate="no">firebase.links.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.links.list" class="permission-name add-link" data-text="firebase.links.list" tabindex="-1"><code dir="ltr" translate="no">firebase.links.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.links.update" class="permission-name add-link" data-text="firebase.links.update" tabindex="-1"><code dir="ltr" translate="no">firebase.links.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.playLinks.get" class="permission-name add-link" data-text="firebase.playLinks.get" tabindex="-1"><code dir="ltr" translate="no">firebase.playLinks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.playLinks.list" class="permission-name add-link" data-text="firebase.playLinks.list" tabindex="-1"><code dir="ltr" translate="no">firebase.playLinks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.playLinks.update" class="permission-name add-link" data-text="firebase.playLinks.update" tabindex="-1"><code dir="ltr" translate="no">firebase.playLinks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase.projects.delete" class="permission-name add-link" data-text="firebase.projects.delete" tabindex="-1"><code dir="ltr" translate="no">firebase.projects.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebase.projects.get" class="permission-name add-link" data-text="firebase.projects.get" tabindex="-1"><code dir="ltr" translate="no">firebase.projects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storage.hmacKeyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebase.projects.update" class="permission-name add-link" data-text="firebase.projects.update" tabindex="-1"><code dir="ltr" translate="no">firebase.projects.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
