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
<td>Firebase Admin
<p>( <code>roles/ firebase.admin</code> )</p>
<p>Full access to Firebase products.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.getKeyString</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>apikeys.keys.lookup</code></p>
<p><code>appengine.applications.get</code></p>
<p><code>artifactregistry. attachments. get</code></p>
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
<p><code>automl.*</code></p>
<ul>
<li><code>automl.annotationSpecs.create</code></li>
<li><code>automl.annotationSpecs.delete</code></li>
<li><code>automl.annotationSpecs.get</code></li>
<li><code>automl.annotationSpecs.list</code></li>
<li><code>automl.annotationSpecs.update</code></li>
<li><code>automl.annotations.approve</code></li>
<li><code>automl.annotations.create</code></li>
<li><code>automl.annotations.list</code></li>
<li><code>automl.annotations.manipulate</code></li>
<li><code>automl.annotations.reject</code></li>
<li><code>automl.columnSpecs.get</code></li>
<li><code>automl.columnSpecs.list</code></li>
<li><code>automl.columnSpecs.update</code></li>
<li><code>automl.datasets.create</code></li>
<li><code>automl.datasets.delete</code></li>
<li><code>automl.datasets.export</code></li>
<li><code>automl.datasets.get</code></li>
<li><code>automl.datasets.getIamPolicy</code></li>
<li><code>automl.datasets.import</code></li>
<li><code>automl.datasets.list</code></li>
<li><code>automl.datasets.setIamPolicy</code></li>
<li><code>automl.datasets.update</code></li>
<li><code>automl.examples.delete</code></li>
<li><code>automl.examples.get</code></li>
<li><code>automl.examples.list</code></li>
<li><code>automl.examples.update</code></li>
<li><code>automl.files.delete</code></li>
<li><code>automl.files.list</code></li>
<li><code>automl. humanAnnotationTasks. create</code></li>
<li><code>automl. humanAnnotationTasks. delete</code></li>
<li><code>automl. humanAnnotationTasks. get</code></li>
<li><code>automl. humanAnnotationTasks. list</code></li>
<li><code>automl.locations.get</code></li>
<li><code>automl.locations.getIamPolicy</code></li>
<li><code>automl.locations.list</code></li>
<li><code>automl.locations.setIamPolicy</code></li>
<li><code>automl.modelEvaluations.create</code></li>
<li><code>automl.modelEvaluations.get</code></li>
<li><code>automl.modelEvaluations.list</code></li>
<li><code>automl.models.create</code></li>
<li><code>automl.models.delete</code></li>
<li><code>automl.models.deploy</code></li>
<li><code>automl.models.export</code></li>
<li><code>automl.models.get</code></li>
<li><code>automl.models.getIamPolicy</code></li>
<li><code>automl.models.list</code></li>
<li><code>automl.models.predict</code></li>
<li><code>automl.models.setIamPolicy</code></li>
<li><code>automl.models.undeploy</code></li>
<li><code>automl.operations.cancel</code></li>
<li><code>automl.operations.delete</code></li>
<li><code>automl.operations.get</code></li>
<li><code>automl.operations.list</code></li>
<li><code>automl.tableSpecs.get</code></li>
<li><code>automl.tableSpecs.list</code></li>
<li><code>automl.tableSpecs.update</code></li>
</ul>
<p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig.brands.update</code></p>
<p><code>clientauthconfig. clients. create</code></p>
<p><code>clientauthconfig. clients. delete</code></p>
<p><code>clientauthconfig.clients.get</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>clientauthconfig. clients. update</code></p>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudconfig.*</code></p>
<ul>
<li><code>cloudconfig.configs.get</code></li>
<li><code>cloudconfig.configs.update</code></li>
</ul>
<p><code>cloudfunctions.*</code></p>
<ul>
<li><code>cloudfunctions.functions.call</code></li>
<li><code>cloudfunctions. functions. create</code></li>
<li><code>cloudfunctions. functions. delete</code></li>
<li><code>cloudfunctions. functions. generationUpgrade</code></li>
<li><code>cloudfunctions.functions.get</code></li>
<li><code>cloudfunctions. functions. getIamPolicy</code></li>
<li><code>cloudfunctions. functions. invoke</code></li>
<li><code>cloudfunctions.functions.list</code></li>
<li><code>cloudfunctions. functions. setIamPolicy</code></li>
<li><code>cloudfunctions. functions. sourceCodeGet</code></li>
<li><code>cloudfunctions. functions. sourceCodeSet</code></li>
<li><code>cloudfunctions. functions. update</code></li>
<li><code>cloudfunctions.locations.list</code></li>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>cloudmessaging.*</code></p>
<ul>
<li><code>cloudmessaging.messages.create</code></li>
<li><code>cloudmessaging. topicSubscriptions. create</code></li>
<li><code>cloudmessaging. topicSubscriptions. delete</code></li>
<li><code>cloudmessaging. topicSubscriptions. get</code></li>
<li><code>cloudmessaging. topicSubscriptions. list</code></li>
<li><code>cloudmessaging. topicSubscriptions. update</code></li>
</ul>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudtestservice. environmentcatalog. get</code></p>
<p><code>cloudtestservice.matrices.*</code></p>
<ul>
<li><code>cloudtestservice. matrices. create</code></li>
<li><code>cloudtestservice.matrices.get</code></li>
<li><code>cloudtestservice. matrices. update</code></li>
</ul>
<p><code>cloudtoolresults.*</code></p>
<ul>
<li><code>cloudtoolresults. executions. create</code></li>
<li><code>cloudtoolresults. executions. get</code></li>
<li><code>cloudtoolresults. executions. list</code></li>
<li><code>cloudtoolresults. executions. update</code></li>
<li><code>cloudtoolresults. histories. create</code></li>
<li><code>cloudtoolresults.histories.get</code></li>
<li><code>cloudtoolresults. histories. list</code></li>
<li><code>cloudtoolresults. settings. create</code></li>
<li><code>cloudtoolresults.settings.get</code></li>
<li><code>cloudtoolresults. settings. update</code></li>
<li><code>cloudtoolresults.steps.create</code></li>
<li><code>cloudtoolresults.steps.get</code></li>
<li><code>cloudtoolresults.steps.list</code></li>
<li><code>cloudtoolresults.steps.update</code></li>
</ul>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries.*</code></p>
<ul>
<li><code>databasesconsole. studioQueries. create</code></li>
<li><code>databasesconsole. studioQueries. delete</code></li>
<li><code>databasesconsole. studioQueries. get</code></li>
<li><code>databasesconsole. studioQueries. list</code></li>
<li><code>databasesconsole. studioQueries. search</code></li>
<li><code>databasesconsole. studioQueries. update</code></li>
</ul>
<p><code>datastore.*</code></p>
<ul>
<li><code>datastore. backupSchedules. create</code></li>
<li><code>datastore. backupSchedules. delete</code></li>
<li><code>datastore.backupSchedules.get</code></li>
<li><code>datastore.backupSchedules.list</code></li>
<li><code>datastore. backupSchedules. update</code></li>
<li><code>datastore.backups.delete</code></li>
<li><code>datastore.backups.get</code></li>
<li><code>datastore.backups.list</code></li>
<li><code>datastore. backups. restoreDatabase</code></li>
<li><code>datastore.databases.bulkDelete</code></li>
<li><code>datastore.databases.clone</code></li>
<li><code>datastore.databases.create</code></li>
<li><code>datastore. databases. createTagBinding</code></li>
<li><code>datastore.databases.delete</code></li>
<li><code>datastore. databases. deleteTagBinding</code></li>
<li><code>datastore.databases.export</code></li>
<li><code>datastore.databases.get</code></li>
<li><code>datastore. databases. getMetadata</code></li>
<li><code>datastore.databases.import</code></li>
<li><code>datastore.databases.list</code></li>
<li><code>datastore. databases. listEffectiveTags</code></li>
<li><code>datastore. databases. listTagBindings</code></li>
<li><code>datastore.databases.update</code></li>
<li><code>datastore.entities.allocateIds</code></li>
<li><code>datastore.entities.create</code></li>
<li><code>datastore.entities.delete</code></li>
<li><code>datastore.entities.get</code></li>
<li><code>datastore.entities.list</code></li>
<li><code>datastore.entities.update</code></li>
<li><code>datastore.insights.get</code></li>
<li><code>datastore. keyVisualizerScans. get</code></li>
<li><code>datastore. keyVisualizerScans. list</code></li>
<li><code>datastore.locations.get</code></li>
<li><code>datastore.locations.list</code></li>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
<li><code>datastore.operations.cancel</code></li>
<li><code>datastore.operations.delete</code></li>
<li><code>datastore.operations.get</code></li>
<li><code>datastore.operations.list</code></li>
<li><code>datastore.schemas.create</code></li>
<li><code>datastore.schemas.delete</code></li>
<li><code>datastore.schemas.get</code></li>
<li><code>datastore.schemas.list</code></li>
<li><code>datastore.schemas.update</code></li>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
<li><code>datastore.userCreds.create</code></li>
<li><code>datastore.userCreds.delete</code></li>
<li><code>datastore.userCreds.get</code></li>
<li><code>datastore.userCreds.list</code></li>
<li><code>datastore.userCreds.update</code></li>
</ul>
<p><code>errorreporting.groups.list</code></p>
<p><code>eventarc.*</code></p>
<ul>
<li><code>eventarc. channelConnections. create</code></li>
<li><code>eventarc. channelConnections. createTagBinding</code></li>
<li><code>eventarc. channelConnections. delete</code></li>
<li><code>eventarc. channelConnections. deleteTagBinding</code></li>
<li><code>eventarc. channelConnections. get</code></li>
<li><code>eventarc. channelConnections. getIamPolicy</code></li>
<li><code>eventarc. channelConnections. list</code></li>
<li><code>eventarc. channelConnections. listEffectiveTags</code></li>
<li><code>eventarc. channelConnections. listTagBindings</code></li>
<li><code>eventarc. channelConnections. publish</code></li>
<li><code>eventarc. channelConnections. setIamPolicy</code></li>
<li><code>eventarc.channels.attach</code></li>
<li><code>eventarc.channels.create</code></li>
<li><code>eventarc. channels. createTagBinding</code></li>
<li><code>eventarc.channels.delete</code></li>
<li><code>eventarc. channels. deleteTagBinding</code></li>
<li><code>eventarc.channels.get</code></li>
<li><code>eventarc.channels.getIamPolicy</code></li>
<li><code>eventarc.channels.list</code></li>
<li><code>eventarc. channels. listEffectiveTags</code></li>
<li><code>eventarc. channels. listTagBindings</code></li>
<li><code>eventarc.channels.publish</code></li>
<li><code>eventarc.channels.setIamPolicy</code></li>
<li><code>eventarc.channels.undelete</code></li>
<li><code>eventarc.channels.update</code></li>
<li><code>eventarc.enrollments.create</code></li>
<li><code>eventarc.enrollments.delete</code></li>
<li><code>eventarc.enrollments.get</code></li>
<li><code>eventarc. enrollments. getIamPolicy</code></li>
<li><code>eventarc.enrollments.list</code></li>
<li><code>eventarc. enrollments. setIamPolicy</code></li>
<li><code>eventarc.enrollments.update</code></li>
<li><code>eventarc. events. receiveAuditLogWritten</code></li>
<li><code>eventarc.events.receiveEvent</code></li>
<li><code>eventarc. googleApiSources. create</code></li>
<li><code>eventarc. googleApiSources. delete</code></li>
<li><code>eventarc.googleApiSources.get</code></li>
<li><code>eventarc. googleApiSources. getIamPolicy</code></li>
<li><code>eventarc.googleApiSources.list</code></li>
<li><code>eventarc. googleApiSources. setIamPolicy</code></li>
<li><code>eventarc. googleApiSources. update</code></li>
<li><code>eventarc. googleChannelConfigs. get</code></li>
<li><code>eventarc. googleChannelConfigs. update</code></li>
<li><code>eventarc.kafkaSources.create</code></li>
<li><code>eventarc.kafkaSources.delete</code></li>
<li><code>eventarc.kafkaSources.get</code></li>
<li><code>eventarc. kafkaSources. getIamPolicy</code></li>
<li><code>eventarc.kafkaSources.list</code></li>
<li><code>eventarc. kafkaSources. setIamPolicy</code></li>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
<li><code>eventarc.messageBuses.create</code></li>
<li><code>eventarc.messageBuses.delete</code></li>
<li><code>eventarc.messageBuses.get</code></li>
<li><code>eventarc. messageBuses. getIamPolicy</code></li>
<li><code>eventarc.messageBuses.list</code></li>
<li><code>eventarc.messageBuses.publish</code></li>
<li><code>eventarc. messageBuses. setIamPolicy</code></li>
<li><code>eventarc.messageBuses.update</code></li>
<li><code>eventarc.messageBuses.use</code></li>
<li><code>eventarc. multiProjectSources. collectGoogleApiEvents</code></li>
<li><code>eventarc.operations.cancel</code></li>
<li><code>eventarc.operations.delete</code></li>
<li><code>eventarc.operations.get</code></li>
<li><code>eventarc.operations.list</code></li>
<li><code>eventarc.pipelines.create</code></li>
<li><code>eventarc.pipelines.delete</code></li>
<li><code>eventarc.pipelines.get</code></li>
<li><code>eventarc. pipelines. getIamPolicy</code></li>
<li><code>eventarc.pipelines.list</code></li>
<li><code>eventarc. pipelines. setIamPolicy</code></li>
<li><code>eventarc.pipelines.update</code></li>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
<li><code>eventarc.triggers.create</code></li>
<li><code>eventarc. triggers. createTagBinding</code></li>
<li><code>eventarc.triggers.delete</code></li>
<li><code>eventarc. triggers. deleteTagBinding</code></li>
<li><code>eventarc.triggers.get</code></li>
<li><code>eventarc.triggers.getIamPolicy</code></li>
<li><code>eventarc.triggers.list</code></li>
<li><code>eventarc. triggers. listEffectiveTags</code></li>
<li><code>eventarc. triggers. listTagBindings</code></li>
<li><code>eventarc.triggers.setIamPolicy</code></li>
<li><code>eventarc.triggers.undelete</code></li>
<li><code>eventarc.triggers.update</code></li>
</ul>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.*</code></p>
<ul>
<li><code>firebase.billingPlans.get</code></li>
<li><code>firebase.billingPlans.update</code></li>
<li><code>firebase.clients.create</code></li>
<li><code>firebase.clients.delete</code></li>
<li><code>firebase.clients.get</code></li>
<li><code>firebase.clients.list</code></li>
<li><code>firebase.clients.undelete</code></li>
<li><code>firebase.clients.update</code></li>
<li><code>firebase.links.create</code></li>
<li><code>firebase.links.delete</code></li>
<li><code>firebase.links.list</code></li>
<li><code>firebase.links.update</code></li>
<li><code>firebase.playLinks.get</code></li>
<li><code>firebase.playLinks.list</code></li>
<li><code>firebase.playLinks.update</code></li>
<li><code>firebase.projects.delete</code></li>
<li><code>firebase.projects.get</code></li>
<li><code>firebase.projects.update</code></li>
</ul>
<p><code>firebaseabt.*</code></p>
<ul>
<li><code>firebaseabt. experimentresults. get</code></li>
<li><code>firebaseabt.experiments.create</code></li>
<li><code>firebaseabt.experiments.delete</code></li>
<li><code>firebaseabt.experiments.get</code></li>
<li><code>firebaseabt.experiments.list</code></li>
<li><code>firebaseabt.experiments.update</code></li>
<li><code>firebaseabt. projectmetadata. get</code></li>
</ul>
<p><code>firebaseanalytics.*</code></p>
<ul>
<li><code>firebaseanalytics. resources. googleAnalyticsEdit</code></li>
<li><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code>firebaseappcheck.*</code></p>
<ul>
<li><code>firebaseappcheck. appAttestConfig. get</code></li>
<li><code>firebaseappcheck. appAttestConfig. update</code></li>
<li><code>firebaseappcheck. appCheckTokens. verify</code></li>
<li><code>firebaseappcheck. automations. create</code></li>
<li><code>firebaseappcheck. automations. delete</code></li>
<li><code>firebaseappcheck. automations. get</code></li>
<li><code>firebaseappcheck. automations. list</code></li>
<li><code>firebaseappcheck. automations. resume</code></li>
<li><code>firebaseappcheck. automations. suspend</code></li>
<li><code>firebaseappcheck. automations. update</code></li>
<li><code>firebaseappcheck. debugTokens. get</code></li>
<li><code>firebaseappcheck. debugTokens. update</code></li>
<li><code>firebaseappcheck. deviceCheckConfig. get</code></li>
<li><code>firebaseappcheck. deviceCheckConfig. update</code></li>
<li><code>firebaseappcheck. playIntegrityConfig. get</code></li>
<li><code>firebaseappcheck. playIntegrityConfig. update</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. update</code></li>
<li><code>firebaseappcheck. recaptchaV3Config. get</code></li>
<li><code>firebaseappcheck. recaptchaV3Config. update</code></li>
<li><code>firebaseappcheck. resourcePolicies. get</code></li>
<li><code>firebaseappcheck. resourcePolicies. update</code></li>
<li><code>firebaseappcheck. safetyNetConfig. get</code></li>
<li><code>firebaseappcheck. safetyNetConfig. update</code></li>
<li><code>firebaseappcheck.services.get</code></li>
<li><code>firebaseappcheck. services. update</code></li>
<li><code>firebaseappcheck.tokens.mint</code></li>
</ul>
<p><code>firebaseappdistro.*</code></p>
<ul>
<li><code>firebaseappdistro.groups.list</code></li>
<li><code>firebaseappdistro. groups. update</code></li>
<li><code>firebaseappdistro. releases. list</code></li>
<li><code>firebaseappdistro. releases. update</code></li>
<li><code>firebaseappdistro.testers.list</code></li>
<li><code>firebaseappdistro. testers. update</code></li>
</ul>
<p><code>firebaseapphosting.*</code></p>
<ul>
<li><code>firebaseapphosting. backends. create</code></li>
<li><code>firebaseapphosting. backends. delete</code></li>
<li><code>firebaseapphosting. backends. get</code></li>
<li><code>firebaseapphosting. backends. list</code></li>
<li><code>firebaseapphosting. backends. update</code></li>
<li><code>firebaseapphosting. builds. create</code></li>
<li><code>firebaseapphosting. builds. delete</code></li>
<li><code>firebaseapphosting.builds.get</code></li>
<li><code>firebaseapphosting.builds.list</code></li>
<li><code>firebaseapphosting. builds. update</code></li>
<li><code>firebaseapphosting. domains. create</code></li>
<li><code>firebaseapphosting. domains. delete</code></li>
<li><code>firebaseapphosting.domains.get</code></li>
<li><code>firebaseapphosting. domains. list</code></li>
<li><code>firebaseapphosting. domains. update</code></li>
<li><code>firebaseapphosting. locations. get</code></li>
<li><code>firebaseapphosting. locations. list</code></li>
<li><code>firebaseapphosting. operations. cancel</code></li>
<li><code>firebaseapphosting. operations. delete</code></li>
<li><code>firebaseapphosting. operations. get</code></li>
<li><code>firebaseapphosting. operations. list</code></li>
<li><code>firebaseapphosting. rollouts. create</code></li>
<li><code>firebaseapphosting. rollouts. delete</code></li>
<li><code>firebaseapphosting. rollouts. get</code></li>
<li><code>firebaseapphosting. rollouts. list</code></li>
<li><code>firebaseapphosting. rollouts. update</code></li>
<li><code>firebaseapphosting.traffic.get</code></li>
<li><code>firebaseapphosting. traffic. update</code></li>
</ul>
<p><code>firebaseauth.*</code></p>
<ul>
<li><code>firebaseauth.configs.create</code></li>
<li><code>firebaseauth.configs.get</code></li>
<li><code>firebaseauth. configs. getHashConfig</code></li>
<li><code>firebaseauth.configs.getSecret</code></li>
<li><code>firebaseauth.configs.update</code></li>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>firebasecrash.*</code></p>
<ul>
<li><code>firebasecrash.issues.update</code></li>
<li><code>firebasecrash.reports.get</code></li>
</ul>
<p><code>firebasecrashlytics.*</code></p>
<ul>
<li><code>firebasecrashlytics.config.get</code></li>
<li><code>firebasecrashlytics. config. update</code></li>
<li><code>firebasecrashlytics.data.get</code></li>
<li><code>firebasecrashlytics.issues.get</code></li>
<li><code>firebasecrashlytics. issues. list</code></li>
<li><code>firebasecrashlytics. issues. update</code></li>
<li><code>firebasecrashlytics. sessions. get</code></li>
</ul>
<p><code>firebasedatabase.*</code></p>
<ul>
<li><code>firebasedatabase. instances. create</code></li>
<li><code>firebasedatabase. instances. delete</code></li>
<li><code>firebasedatabase. instances. disable</code></li>
<li><code>firebasedatabase.instances.get</code></li>
<li><code>firebasedatabase. instances. list</code></li>
<li><code>firebasedatabase. instances. reenable</code></li>
<li><code>firebasedatabase. instances. undelete</code></li>
<li><code>firebasedatabase. instances. update</code></li>
</ul>
<p><code>firebasedataconnect.*</code></p>
<ul>
<li><code>firebasedataconnect. connectorRevisions. delete</code></li>
<li><code>firebasedataconnect. connectorRevisions. get</code></li>
<li><code>firebasedataconnect. connectorRevisions. list</code></li>
<li><code>firebasedataconnect. connectors. create</code></li>
<li><code>firebasedataconnect. connectors. delete</code></li>
<li><code>firebasedataconnect. connectors. get</code></li>
<li><code>firebasedataconnect. connectors. impersonateMutation</code></li>
<li><code>firebasedataconnect. connectors. impersonateQuery</code></li>
<li><code>firebasedataconnect. connectors. list</code></li>
<li><code>firebasedataconnect. connectors. update</code></li>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
<li><code>firebasedataconnect. operations. cancel</code></li>
<li><code>firebasedataconnect. operations. delete</code></li>
<li><code>firebasedataconnect. operations. get</code></li>
<li><code>firebasedataconnect. operations. list</code></li>
<li><code>firebasedataconnect. schemaRevisions. delete</code></li>
<li><code>firebasedataconnect. schemaRevisions. get</code></li>
<li><code>firebasedataconnect. schemaRevisions. list</code></li>
<li><code>firebasedataconnect. schemas. create</code></li>
<li><code>firebasedataconnect. schemas. delete</code></li>
<li><code>firebasedataconnect. schemas. get</code></li>
<li><code>firebasedataconnect. schemas. list</code></li>
<li><code>firebasedataconnect. schemas. migrate</code></li>
<li><code>firebasedataconnect. schemas. update</code></li>
<li><code>firebasedataconnect. services. create</code></li>
<li><code>firebasedataconnect. services. delete</code></li>
<li><code>firebasedataconnect. services. executeGraphql</code></li>
<li><code>firebasedataconnect. services. executeGraphqlRead</code></li>
<li><code>firebasedataconnect. services. generateQuery</code></li>
<li><code>firebasedataconnect. services. generateSchema</code></li>
<li><code>firebasedataconnect. services. get</code></li>
<li><code>firebasedataconnect. services. introspectGraphql</code></li>
<li><code>firebasedataconnect. services. list</code></li>
<li><code>firebasedataconnect. services. update</code></li>
</ul>
<p><code>firebasedynamiclinks.*</code></p>
<ul>
<li><code>firebasedynamiclinks. destinations. list</code></li>
<li><code>firebasedynamiclinks. destinations. update</code></li>
<li><code>firebasedynamiclinks. domains. create</code></li>
<li><code>firebasedynamiclinks. domains. delete</code></li>
<li><code>firebasedynamiclinks. domains. get</code></li>
<li><code>firebasedynamiclinks. domains. list</code></li>
<li><code>firebasedynamiclinks. domains. update</code></li>
<li><code>firebasedynamiclinks. links. create</code></li>
<li><code>firebasedynamiclinks.links.get</code></li>
<li><code>firebasedynamiclinks. links. list</code></li>
<li><code>firebasedynamiclinks. links. update</code></li>
<li><code>firebasedynamiclinks.stats.get</code></li>
</ul>
<p><code>firebaseextensions.*</code></p>
<ul>
<li><code>firebaseextensions. configs. create</code></li>
<li><code>firebaseextensions. configs. delete</code></li>
<li><code>firebaseextensions. configs. list</code></li>
<li><code>firebaseextensions. configs. update</code></li>
</ul>
<p><code>firebaseextensionspublisher.*</code></p>
<ul>
<li><code>firebaseextensionspublisher. extensions. create</code></li>
<li><code>firebaseextensionspublisher. extensions. delete</code></li>
<li><code>firebaseextensionspublisher. extensions. get</code></li>
<li><code>firebaseextensionspublisher. extensions. list</code></li>
</ul>
<p><code>firebasehosting.*</code></p>
<ul>
<li><code>firebasehosting.sites.create</code></li>
<li><code>firebasehosting.sites.delete</code></li>
<li><code>firebasehosting.sites.get</code></li>
<li><code>firebasehosting.sites.list</code></li>
<li><code>firebasehosting.sites.update</code></li>
</ul>
<p><code>firebaseinappmessaging.*</code></p>
<ul>
<li><code>firebaseinappmessaging. campaigns. create</code></li>
<li><code>firebaseinappmessaging. campaigns. delete</code></li>
<li><code>firebaseinappmessaging. campaigns. get</code></li>
<li><code>firebaseinappmessaging. campaigns. list</code></li>
<li><code>firebaseinappmessaging. campaigns. update</code></li>
</ul>
<p><code>firebasemessagingcampaigns.*</code></p>
<ul>
<li><code>firebasemessagingcampaigns. campaigns. create</code></li>
<li><code>firebasemessagingcampaigns. campaigns. delete</code></li>
<li><code>firebasemessagingcampaigns. campaigns. get</code></li>
<li><code>firebasemessagingcampaigns. campaigns. list</code></li>
<li><code>firebasemessagingcampaigns. campaigns. start</code></li>
<li><code>firebasemessagingcampaigns. campaigns. stop</code></li>
<li><code>firebasemessagingcampaigns. campaigns. update</code></li>
</ul>
<p><code>firebaseml.*</code></p>
<ul>
<li><code>firebaseml.models.create</code></li>
<li><code>firebaseml.models.delete</code></li>
<li><code>firebaseml.models.get</code></li>
<li><code>firebaseml.models.list</code></li>
<li><code>firebaseml.models.update</code></li>
<li><code>firebaseml. modelversions. create</code></li>
<li><code>firebaseml.modelversions.get</code></li>
<li><code>firebaseml.modelversions.list</code></li>
<li><code>firebaseml. modelversions. update</code></li>
</ul>
<p><code>firebasenotifications.*</code></p>
<ul>
<li><code>firebasenotifications. messages. create</code></li>
<li><code>firebasenotifications. messages. delete</code></li>
<li><code>firebasenotifications. messages. get</code></li>
<li><code>firebasenotifications. messages. list</code></li>
<li><code>firebasenotifications. messages. update</code></li>
</ul>
<p><code>firebaseperformance.*</code></p>
<ul>
<li><code>firebaseperformance. config. update</code></li>
<li><code>firebaseperformance.data.get</code></li>
</ul>
<p><code>firebaserules.*</code></p>
<ul>
<li><code>firebaserules.releases.create</code></li>
<li><code>firebaserules.releases.delete</code></li>
<li><code>firebaserules.releases.get</code></li>
<li><code>firebaserules. releases. getExecutable</code></li>
<li><code>firebaserules.releases.list</code></li>
<li><code>firebaserules.releases.update</code></li>
<li><code>firebaserules.rulesets.create</code></li>
<li><code>firebaserules.rulesets.delete</code></li>
<li><code>firebaserules.rulesets.get</code></li>
<li><code>firebaserules.rulesets.list</code></li>
<li><code>firebaserules.rulesets.test</code></li>
</ul>
<p><code>firebasestorage.*</code></p>
<ul>
<li><code>firebasestorage. buckets. addFirebase</code></li>
<li><code>firebasestorage.buckets.get</code></li>
<li><code>firebasestorage.buckets.list</code></li>
<li><code>firebasestorage. buckets. removeFirebase</code></li>
<li><code>firebasestorage. defaultBucket. create</code></li>
<li><code>firebasestorage. defaultBucket. delete</code></li>
<li><code>firebasestorage. defaultBucket. get</code></li>
</ul>
<p><code>firebasevertexai.*</code></p>
<ul>
<li><code>firebasevertexai.configs.get</code></li>
<li><code>firebasevertexai. configs. update</code></li>
<li><code>firebasevertexai. promptTemplates. create</code></li>
<li><code>firebasevertexai. promptTemplates. delete</code></li>
<li><code>firebasevertexai. promptTemplates. get</code></li>
<li><code>firebasevertexai. promptTemplates. list</code></li>
<li><code>firebasevertexai. promptTemplates. update</code></li>
<li><code>firebasevertexai. promptTemplates. updateLock</code></li>
</ul>
<p><code>logging.logEntries.download</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.views.access</code></p>
<p><code>logging.views.listLogs</code></p>
<p><code>logging.views.listResourceKeys</code></p>
<p><code>logging. views. listResourceValues</code></p>
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
<p><code>oauthconfig.verification.get</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights.*</code></p>
<ul>
<li><code>recommender. cloudFunctionsPerformanceInsights. get</code></li>
<li><code>recommender. cloudFunctionsPerformanceInsights. list</code></li>
<li><code>recommender. cloudFunctionsPerformanceInsights. update</code></li>
</ul>
<p><code>recommender. cloudFunctionsPerformanceRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudFunctionsPerformanceRecommendations. get</code></li>
<li><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></li>
<li><code>recommender. cloudFunctionsPerformanceRecommendations. update</code></li>
</ul>
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
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. runServiceCostInsights.*</code></p>
<ul>
<li><code>recommender. runServiceCostInsights. get</code></li>
<li><code>recommender. runServiceCostInsights. list</code></li>
<li><code>recommender. runServiceCostInsights. update</code></li>
</ul>
<p><code>recommender. runServiceCostRecommendations.*</code></p>
<ul>
<li><code>recommender. runServiceCostRecommendations. get</code></li>
<li><code>recommender. runServiceCostRecommendations. list</code></li>
<li><code>recommender. runServiceCostRecommendations. update</code></li>
</ul>
<p><code>recommender. runServiceIdentityInsights.*</code></p>
<ul>
<li><code>recommender. runServiceIdentityInsights. get</code></li>
<li><code>recommender. runServiceIdentityInsights. list</code></li>
<li><code>recommender. runServiceIdentityInsights. update</code></li>
</ul>
<p><code>recommender. runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code>recommender. runServiceIdentityRecommendations. get</code></li>
<li><code>recommender. runServiceIdentityRecommendations. list</code></li>
<li><code>recommender. runServiceIdentityRecommendations. update</code></li>
</ul>
<p><code>recommender. runServicePerformanceInsights.*</code></p>
<ul>
<li><code>recommender. runServicePerformanceInsights. get</code></li>
<li><code>recommender. runServicePerformanceInsights. list</code></li>
<li><code>recommender. runServicePerformanceInsights. update</code></li>
</ul>
<p><code>recommender. runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code>recommender. runServicePerformanceRecommendations. get</code></li>
<li><code>recommender. runServicePerformanceRecommendations. list</code></li>
<li><code>recommender. runServicePerformanceRecommendations. update</code></li>
</ul>
<p><code>recommender. runServiceSecurityInsights.*</code></p>
<ul>
<li><code>recommender. runServiceSecurityInsights. get</code></li>
<li><code>recommender. runServiceSecurityInsights. list</code></li>
<li><code>recommender. runServiceSecurityInsights. update</code></li>
</ul>
<p><code>recommender. runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code>recommender. runServiceSecurityRecommendations. get</code></li>
<li><code>recommender. runServiceSecurityRecommendations. list</code></li>
<li><code>recommender. runServiceSecurityRecommendations. update</code></li>
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
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
<li><code>run.executions.cancel</code></li>
<li><code>run.executions.delete</code></li>
<li><code>run.executions.get</code></li>
<li><code>run.executions.list</code></li>
<li><code>run.instances.create</code></li>
<li><code>run.instances.delete</code></li>
<li><code>run.instances.get</code></li>
<li><code>run.instances.getIamPolicy</code></li>
<li><code>run.instances.invoke</code></li>
<li><code>run.instances.list</code></li>
<li><code>run.instances.setIamPolicy</code></li>
<li><code>run.instances.sshRead</code></li>
<li><code>run.instances.sshRoot</code></li>
<li><code>run.instances.start</code></li>
<li><code>run.instances.stop</code></li>
<li><code>run.instances.update</code></li>
<li><code>run.jobs.create</code></li>
<li><code>run.jobs.createTagBinding</code></li>
<li><code>run.jobs.delete</code></li>
<li><code>run.jobs.deleteTagBinding</code></li>
<li><code>run.jobs.get</code></li>
<li><code>run.jobs.getIamPolicy</code></li>
<li><code>run.jobs.list</code></li>
<li><code>run.jobs.listEffectiveTags</code></li>
<li><code>run.jobs.listTagBindings</code></li>
<li><code>run.jobs.run</code></li>
<li><code>run.jobs.runWithOverrides</code></li>
<li><code>run.jobs.setIamPolicy</code></li>
<li><code>run.jobs.sshRead</code></li>
<li><code>run.jobs.sshRoot</code></li>
<li><code>run.jobs.update</code></li>
<li><code>run.locations.list</code></li>
<li><code>run.locations.uploadSource</code></li>
<li><code>run.operations.delete</code></li>
<li><code>run.operations.get</code></li>
<li><code>run.operations.list</code></li>
<li><code>run.prompts.get</code></li>
<li><code>run.revisions.delete</code></li>
<li><code>run.revisions.get</code></li>
<li><code>run.revisions.list</code></li>
<li><code>run.routes.get</code></li>
<li><code>run.routes.invoke</code></li>
<li><code>run.routes.list</code></li>
<li><code>run.services.create</code></li>
<li><code>run.services.createTagBinding</code></li>
<li><code>run.services.delete</code></li>
<li><code>run.services.deleteTagBinding</code></li>
<li><code>run.services.get</code></li>
<li><code>run.services.getIamPolicy</code></li>
<li><code>run.services.list</code></li>
<li><code>run.services.listEffectiveTags</code></li>
<li><code>run.services.listTagBindings</code></li>
<li><code>run.services.setIamPolicy</code></li>
<li><code>run.services.sshRead</code></li>
<li><code>run.services.sshRoot</code></li>
<li><code>run.services.update</code></li>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
<li><code>run.workerpools.create</code></li>
<li><code>run.workerpools.delete</code></li>
<li><code>run.workerpools.get</code></li>
<li><code>run.workerpools.getIamPolicy</code></li>
<li><code>run.workerpools.list</code></li>
<li><code>run.workerpools.setIamPolicy</code></li>
<li><code>run.workerpools.sshRead</code></li>
<li><code>run.workerpools.sshRoot</code></li>
<li><code>run.workerpools.update</code></li>
</ul>
<p><code>runtimeconfig.configs.create</code></p>
<p><code>runtimeconfig.configs.delete</code></p>
<p><code>runtimeconfig.configs.get</code></p>
<p><code>runtimeconfig.configs.list</code></p>
<p><code>runtimeconfig.configs.update</code></p>
<p><code>runtimeconfig.operations.*</code></p>
<ul>
<li><code>runtimeconfig.operations.get</code></li>
<li><code>runtimeconfig.operations.list</code></li>
</ul>
<p><code>runtimeconfig.variables.create</code></p>
<p><code>runtimeconfig.variables.delete</code></p>
<p><code>runtimeconfig.variables.get</code></p>
<p><code>runtimeconfig.variables.list</code></p>
<p><code>runtimeconfig.variables.update</code></p>
<p><code>runtimeconfig.variables.watch</code></p>
<p><code>runtimeconfig.waiters.create</code></p>
<p><code>runtimeconfig.waiters.delete</code></p>
<p><code>runtimeconfig.waiters.get</code></p>
<p><code>runtimeconfig.waiters.list</code></p>
<p><code>runtimeconfig.waiters.update</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
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
<tr class="even">
<td>Firebase Editor
<p>( <code>roles/ firebase.editor</code> )</p>
<p>Editor access to Firebase products.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>automl.annotationSpecs.get</code></p>
<p><code>automl.annotationSpecs.list</code></p>
<p><code>automl.annotations.list</code></p>
<p><code>automl.columnSpecs.get</code></p>
<p><code>automl.columnSpecs.list</code></p>
<p><code>automl.datasets.get</code></p>
<p><code>automl.datasets.list</code></p>
<p><code>automl.examples.get</code></p>
<p><code>automl.examples.list</code></p>
<p><code>automl.files.list</code></p>
<p><code>automl. humanAnnotationTasks. get</code></p>
<p><code>automl. humanAnnotationTasks. list</code></p>
<p><code>automl.locations.get</code></p>
<p><code>automl.locations.list</code></p>
<p><code>automl.modelEvaluations.get</code></p>
<p><code>automl.modelEvaluations.list</code></p>
<p><code>automl.models.get</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.operations.get</code></p>
<p><code>automl.operations.list</code></p>
<p><code>automl.tableSpecs.get</code></p>
<p><code>automl.tableSpecs.list</code></p>
<p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudconfig.*</code></p>
<ul>
<li><code>cloudconfig.configs.get</code></li>
<li><code>cloudconfig.configs.update</code></li>
</ul>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.*</code></p>
<ul>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>cloudmessaging. topicSubscriptions. get</code></p>
<p><code>cloudmessaging. topicSubscriptions. list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudtestservice.*</code></p>
<ul>
<li><code>cloudtestservice. devicesession. cancel</code></li>
<li><code>cloudtestservice. devicesession. create</code></li>
<li><code>cloudtestservice. devicesession. get</code></li>
<li><code>cloudtestservice. devicesession. list</code></li>
<li><code>cloudtestservice. devicesession. update</code></li>
<li><code>cloudtestservice. devicesession. use</code></li>
<li><code>cloudtestservice. environmentcatalog. get</code></li>
<li><code>cloudtestservice. matrices. create</code></li>
<li><code>cloudtestservice.matrices.get</code></li>
<li><code>cloudtestservice. matrices. update</code></li>
</ul>
<p><code>cloudtoolresults.*</code></p>
<ul>
<li><code>cloudtoolresults. executions. create</code></li>
<li><code>cloudtoolresults. executions. get</code></li>
<li><code>cloudtoolresults. executions. list</code></li>
<li><code>cloudtoolresults. executions. update</code></li>
<li><code>cloudtoolresults. histories. create</code></li>
<li><code>cloudtoolresults.histories.get</code></li>
<li><code>cloudtoolresults. histories. list</code></li>
<li><code>cloudtoolresults. settings. create</code></li>
<li><code>cloudtoolresults.settings.get</code></li>
<li><code>cloudtoolresults. settings. update</code></li>
<li><code>cloudtoolresults.steps.create</code></li>
<li><code>cloudtoolresults.steps.get</code></li>
<li><code>cloudtoolresults.steps.list</code></li>
<li><code>cloudtoolresults.steps.update</code></li>
</ul>
<p><code>datastore.backups.get</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.entities.get</code></p>
<p><code>datastore.entities.list</code></p>
<p><code>datastore.namespaces.*</code></p>
<ul>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
</ul>
<p><code>datastore.schemas.get</code></p>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.*</code></p>
<ul>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
</ul>
<p><code>datastore.userCreds.get</code></p>
<p><code>datastore.userCreds.list</code></p>
<p><code>errorreporting.groups.list</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc.enrollments.get</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.googleApiSources.get</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleChannelConfigs. get</code></p>
<p><code>eventarc.kafkaSources.get</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc.locations.*</code></p>
<ul>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
</ul>
<p><code>eventarc.messageBuses.get</code></p>
<p><code>eventarc. messageBuses. getIamPolicy</code></p>
<p><code>eventarc.messageBuses.list</code></p>
<p><code>eventarc.messageBuses.use</code></p>
<p><code>eventarc. multiProjectSources. collectGoogleApiEvents</code></p>
<p><code>eventarc.operations.get</code></p>
<p><code>eventarc.operations.list</code></p>
<p><code>eventarc.pipelines.get</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.providers.*</code></p>
<ul>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
</ul>
<p><code>eventarc.triggers.get</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.*</code></p>
<ul>
<li><code>firebase.clients.create</code></li>
<li><code>firebase.clients.delete</code></li>
<li><code>firebase.clients.get</code></li>
<li><code>firebase.clients.list</code></li>
<li><code>firebase.clients.undelete</code></li>
<li><code>firebase.clients.update</code></li>
</ul>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebase.projects.update</code></p>
<p><code>firebaseabt.*</code></p>
<ul>
<li><code>firebaseabt. experimentresults. get</code></li>
<li><code>firebaseabt.experiments.create</code></li>
<li><code>firebaseabt.experiments.delete</code></li>
<li><code>firebaseabt.experiments.get</code></li>
<li><code>firebaseabt.experiments.list</code></li>
<li><code>firebaseabt.experiments.update</code></li>
<li><code>firebaseabt. projectmetadata. get</code></li>
</ul>
<p><code>firebaseanalytics.*</code></p>
<ul>
<li><code>firebaseanalytics. resources. googleAnalyticsEdit</code></li>
<li><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code>firebaseappcheck. appAttestConfig. get</code></p>
<p><code>firebaseappcheck. automations. get</code></p>
<p><code>firebaseappcheck. automations. list</code></p>
<p><code>firebaseappcheck. debugTokens. get</code></p>
<p><code>firebaseappcheck. deviceCheckConfig. get</code></p>
<p><code>firebaseappcheck. playIntegrityConfig. get</code></p>
<p><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></p>
<p><code>firebaseappcheck. recaptchaV3Config. get</code></p>
<p><code>firebaseappcheck. resourcePolicies. get</code></p>
<p><code>firebaseappcheck. safetyNetConfig. get</code></p>
<p><code>firebaseappcheck.services.get</code></p>
<p><code>firebaseappdistro.*</code></p>
<ul>
<li><code>firebaseappdistro.groups.list</code></li>
<li><code>firebaseappdistro. groups. update</code></li>
<li><code>firebaseappdistro. releases. list</code></li>
<li><code>firebaseappdistro. releases. update</code></li>
<li><code>firebaseappdistro.testers.list</code></li>
<li><code>firebaseappdistro. testers. update</code></li>
</ul>
<p><code>firebaseapphosting. backends. get</code></p>
<p><code>firebaseapphosting. backends. list</code></p>
<p><code>firebaseapphosting.builds.get</code></p>
<p><code>firebaseapphosting.builds.list</code></p>
<p><code>firebaseapphosting.domains.get</code></p>
<p><code>firebaseapphosting. domains. list</code></p>
<p><code>firebaseapphosting.locations.*</code></p>
<ul>
<li><code>firebaseapphosting. locations. get</code></li>
<li><code>firebaseapphosting. locations. list</code></li>
</ul>
<p><code>firebaseapphosting. operations. get</code></p>
<p><code>firebaseapphosting. operations. list</code></p>
<p><code>firebaseapphosting. rollouts. get</code></p>
<p><code>firebaseapphosting. rollouts. list</code></p>
<p><code>firebaseapphosting.traffic.get</code></p>
<p><code>firebaseauth.*</code></p>
<ul>
<li><code>firebaseauth.configs.create</code></li>
<li><code>firebaseauth.configs.get</code></li>
<li><code>firebaseauth. configs. getHashConfig</code></li>
<li><code>firebaseauth.configs.getSecret</code></li>
<li><code>firebaseauth.configs.update</code></li>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>firebasecrash.*</code></p>
<ul>
<li><code>firebasecrash.issues.update</code></li>
<li><code>firebasecrash.reports.get</code></li>
</ul>
<p><code>firebasecrashlytics.*</code></p>
<ul>
<li><code>firebasecrashlytics.config.get</code></li>
<li><code>firebasecrashlytics. config. update</code></li>
<li><code>firebasecrashlytics.data.get</code></li>
<li><code>firebasecrashlytics.issues.get</code></li>
<li><code>firebasecrashlytics. issues. list</code></li>
<li><code>firebasecrashlytics. issues. update</code></li>
<li><code>firebasecrashlytics. sessions. get</code></li>
</ul>
<p><code>firebasedatabase.*</code></p>
<ul>
<li><code>firebasedatabase. instances. create</code></li>
<li><code>firebasedatabase. instances. delete</code></li>
<li><code>firebasedatabase. instances. disable</code></li>
<li><code>firebasedatabase.instances.get</code></li>
<li><code>firebasedatabase. instances. list</code></li>
<li><code>firebasedatabase. instances. reenable</code></li>
<li><code>firebasedatabase. instances. undelete</code></li>
<li><code>firebasedatabase. instances. update</code></li>
</ul>
<p><code>firebasedataconnect. connectorRevisions. get</code></p>
<p><code>firebasedataconnect. connectorRevisions. list</code></p>
<p><code>firebasedataconnect. connectors. get</code></p>
<p><code>firebasedataconnect. connectors. list</code></p>
<p><code>firebasedataconnect. locations.*</code></p>
<ul>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
</ul>
<p><code>firebasedataconnect. operations. get</code></p>
<p><code>firebasedataconnect. operations. list</code></p>
<p><code>firebasedataconnect. schemaRevisions. get</code></p>
<p><code>firebasedataconnect. schemaRevisions. list</code></p>
<p><code>firebasedataconnect. schemas. get</code></p>
<p><code>firebasedataconnect. schemas. list</code></p>
<p><code>firebasedataconnect. services. generateQuery</code></p>
<p><code>firebasedataconnect. services. generateSchema</code></p>
<p><code>firebasedataconnect. services. get</code></p>
<p><code>firebasedataconnect. services. introspectGraphql</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebasedynamiclinks. destinations. list</code></p>
<p><code>firebasedynamiclinks. domains. create</code></p>
<p><code>firebasedynamiclinks. domains. get</code></p>
<p><code>firebasedynamiclinks. domains. list</code></p>
<p><code>firebasedynamiclinks. domains. update</code></p>
<p><code>firebasedynamiclinks.links.*</code></p>
<ul>
<li><code>firebasedynamiclinks. links. create</code></li>
<li><code>firebasedynamiclinks.links.get</code></li>
<li><code>firebasedynamiclinks. links. list</code></li>
<li><code>firebasedynamiclinks. links. update</code></li>
</ul>
<p><code>firebasedynamiclinks.stats.get</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseextensionspublisher.*</code></p>
<ul>
<li><code>firebaseextensionspublisher. extensions. create</code></li>
<li><code>firebaseextensionspublisher. extensions. delete</code></li>
<li><code>firebaseextensionspublisher. extensions. get</code></li>
<li><code>firebaseextensionspublisher. extensions. list</code></li>
</ul>
<p><code>firebasehosting.*</code></p>
<ul>
<li><code>firebasehosting.sites.create</code></li>
<li><code>firebasehosting.sites.delete</code></li>
<li><code>firebasehosting.sites.get</code></li>
<li><code>firebasehosting.sites.list</code></li>
<li><code>firebasehosting.sites.update</code></li>
</ul>
<p><code>firebaseinappmessaging.*</code></p>
<ul>
<li><code>firebaseinappmessaging. campaigns. create</code></li>
<li><code>firebaseinappmessaging. campaigns. delete</code></li>
<li><code>firebaseinappmessaging. campaigns. get</code></li>
<li><code>firebaseinappmessaging. campaigns. list</code></li>
<li><code>firebaseinappmessaging. campaigns. update</code></li>
</ul>
<p><code>firebasemessagingcampaigns. campaigns. get</code></p>
<p><code>firebasemessagingcampaigns. campaigns. list</code></p>
<p><code>firebaseml.*</code></p>
<ul>
<li><code>firebaseml.models.create</code></li>
<li><code>firebaseml.models.delete</code></li>
<li><code>firebaseml.models.get</code></li>
<li><code>firebaseml.models.list</code></li>
<li><code>firebaseml.models.update</code></li>
<li><code>firebaseml. modelversions. create</code></li>
<li><code>firebaseml.modelversions.get</code></li>
<li><code>firebaseml.modelversions.list</code></li>
<li><code>firebaseml. modelversions. update</code></li>
</ul>
<p><code>firebasenotifications.*</code></p>
<ul>
<li><code>firebasenotifications. messages. create</code></li>
<li><code>firebasenotifications. messages. delete</code></li>
<li><code>firebasenotifications. messages. get</code></li>
<li><code>firebasenotifications. messages. list</code></li>
<li><code>firebasenotifications. messages. update</code></li>
</ul>
<p><code>firebaseperformance.*</code></p>
<ul>
<li><code>firebaseperformance. config. update</code></li>
<li><code>firebaseperformance.data.get</code></li>
</ul>
<p><code>firebaserules.*</code></p>
<ul>
<li><code>firebaserules.releases.create</code></li>
<li><code>firebaserules.releases.delete</code></li>
<li><code>firebaserules.releases.get</code></li>
<li><code>firebaserules. releases. getExecutable</code></li>
<li><code>firebaserules.releases.list</code></li>
<li><code>firebaserules.releases.update</code></li>
<li><code>firebaserules.rulesets.create</code></li>
<li><code>firebaserules.rulesets.delete</code></li>
<li><code>firebaserules.rulesets.get</code></li>
<li><code>firebaserules.rulesets.list</code></li>
<li><code>firebaserules.rulesets.test</code></li>
</ul>
<p><code>firebasestorage.buckets.get</code></p>
<p><code>firebasestorage.buckets.list</code></p>
<p><code>firebasestorage. defaultBucket. get</code></p>
<p><code>firebasevertexai.configs.get</code></p>
<p><code>firebasevertexai. promptTemplates. get</code></p>
<p><code>firebasevertexai. promptTemplates. list</code></p>
<p><code>logging.logEntries.download</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.views.access</code></p>
<p><code>logging.views.listLogs</code></p>
<p><code>logging.views.listResourceKeys</code></p>
<p><code>logging. views. listResourceValues</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>oauthconfig.verification.get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. runServiceCostInsights. get</code></p>
<p><code>recommender. runServiceCostInsights. list</code></p>
<p><code>recommender. runServiceCostRecommendations. get</code></p>
<p><code>recommender. runServiceCostRecommendations. list</code></p>
<p><code>recommender. runServiceIdentityInsights. get</code></p>
<p><code>recommender. runServiceIdentityInsights. list</code></p>
<p><code>recommender. runServiceIdentityRecommendations. get</code></p>
<p><code>recommender. runServiceIdentityRecommendations. list</code></p>
<p><code>recommender. runServicePerformanceInsights. get</code></p>
<p><code>recommender. runServicePerformanceInsights. list</code></p>
<p><code>recommender. runServicePerformanceRecommendations. get</code></p>
<p><code>recommender. runServicePerformanceRecommendations. list</code></p>
<p><code>recommender. runServiceSecurityInsights. get</code></p>
<p><code>recommender. runServiceSecurityInsights. list</code></p>
<p><code>recommender. runServiceSecurityRecommendations. get</code></p>
<p><code>recommender. runServiceSecurityRecommendations. list</code></p>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.configurations.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
</ul>
<p><code>run.executions.get</code></p>
<p><code>run.executions.list</code></p>
<p><code>run.instances.get</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.locations.list</code></p>
<p><code>run.operations.get</code></p>
<p><code>run.operations.list</code></p>
<p><code>run.prompts.get</code></p>
<p><code>run.revisions.get</code></p>
<p><code>run.revisions.list</code></p>
<p><code>run.routes.get</code></p>
<p><code>run.routes.list</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>run.tasks.*</code></p>
<ul>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
</ul>
<p><code>run.workerpools.get</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Viewer
<p>( <code>roles/ firebase.viewer</code> )</p>
<p>Read-only access to Firebase products.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>automl.annotationSpecs.get</code></p>
<p><code>automl.annotationSpecs.list</code></p>
<p><code>automl.annotations.list</code></p>
<p><code>automl.columnSpecs.get</code></p>
<p><code>automl.columnSpecs.list</code></p>
<p><code>automl.datasets.get</code></p>
<p><code>automl.datasets.list</code></p>
<p><code>automl.examples.get</code></p>
<p><code>automl.examples.list</code></p>
<p><code>automl.files.list</code></p>
<p><code>automl. humanAnnotationTasks. get</code></p>
<p><code>automl. humanAnnotationTasks. list</code></p>
<p><code>automl.locations.get</code></p>
<p><code>automl.locations.list</code></p>
<p><code>automl.modelEvaluations.get</code></p>
<p><code>automl.modelEvaluations.list</code></p>
<p><code>automl.models.get</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.operations.get</code></p>
<p><code>automl.operations.list</code></p>
<p><code>automl.tableSpecs.get</code></p>
<p><code>automl.tableSpecs.list</code></p>
<p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudconfig.configs.get</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.*</code></p>
<ul>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>cloudmessaging. topicSubscriptions. get</code></p>
<p><code>cloudmessaging. topicSubscriptions. list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudtestservice. environmentcatalog. get</code></p>
<p><code>cloudtestservice.matrices.get</code></p>
<p><code>cloudtoolresults. executions. get</code></p>
<p><code>cloudtoolresults. executions. list</code></p>
<p><code>cloudtoolresults.histories.get</code></p>
<p><code>cloudtoolresults. histories. list</code></p>
<p><code>cloudtoolresults.settings.get</code></p>
<p><code>cloudtoolresults.steps.get</code></p>
<p><code>cloudtoolresults.steps.list</code></p>
<p><code>datastore.backups.get</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.entities.get</code></p>
<p><code>datastore.entities.list</code></p>
<p><code>datastore.namespaces.*</code></p>
<ul>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
</ul>
<p><code>datastore.schemas.get</code></p>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.*</code></p>
<ul>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
</ul>
<p><code>datastore.userCreds.get</code></p>
<p><code>datastore.userCreds.list</code></p>
<p><code>errorreporting.groups.list</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc.enrollments.get</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.googleApiSources.get</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleChannelConfigs. get</code></p>
<p><code>eventarc.kafkaSources.get</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc.locations.*</code></p>
<ul>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
</ul>
<p><code>eventarc.messageBuses.get</code></p>
<p><code>eventarc. messageBuses. getIamPolicy</code></p>
<p><code>eventarc.messageBuses.list</code></p>
<p><code>eventarc.messageBuses.use</code></p>
<p><code>eventarc. multiProjectSources. collectGoogleApiEvents</code></p>
<p><code>eventarc.operations.get</code></p>
<p><code>eventarc.operations.list</code></p>
<p><code>eventarc.pipelines.get</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.providers.*</code></p>
<ul>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
</ul>
<p><code>eventarc.triggers.get</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseabt. experimentresults. get</code></p>
<p><code>firebaseabt.experiments.get</code></p>
<p><code>firebaseabt.experiments.list</code></p>
<p><code>firebaseabt. projectmetadata. get</code></p>
<p><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></p>
<p><code>firebaseappcheck. appAttestConfig. get</code></p>
<p><code>firebaseappcheck. automations. get</code></p>
<p><code>firebaseappcheck. automations. list</code></p>
<p><code>firebaseappcheck. debugTokens. get</code></p>
<p><code>firebaseappcheck. deviceCheckConfig. get</code></p>
<p><code>firebaseappcheck. playIntegrityConfig. get</code></p>
<p><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></p>
<p><code>firebaseappcheck. recaptchaV3Config. get</code></p>
<p><code>firebaseappcheck. resourcePolicies. get</code></p>
<p><code>firebaseappcheck. safetyNetConfig. get</code></p>
<p><code>firebaseappcheck.services.get</code></p>
<p><code>firebaseappdistro.groups.list</code></p>
<p><code>firebaseappdistro. releases. list</code></p>
<p><code>firebaseappdistro.testers.list</code></p>
<p><code>firebaseapphosting. backends. get</code></p>
<p><code>firebaseapphosting. backends. list</code></p>
<p><code>firebaseapphosting.builds.get</code></p>
<p><code>firebaseapphosting.builds.list</code></p>
<p><code>firebaseapphosting.domains.get</code></p>
<p><code>firebaseapphosting. domains. list</code></p>
<p><code>firebaseapphosting.locations.*</code></p>
<ul>
<li><code>firebaseapphosting. locations. get</code></li>
<li><code>firebaseapphosting. locations. list</code></li>
</ul>
<p><code>firebaseapphosting. operations. get</code></p>
<p><code>firebaseapphosting. operations. list</code></p>
<p><code>firebaseapphosting. rollouts. get</code></p>
<p><code>firebaseapphosting. rollouts. list</code></p>
<p><code>firebaseapphosting.traffic.get</code></p>
<p><code>firebaseauth.configs.get</code></p>
<p><code>firebaseauth.users.get</code></p>
<p><code>firebasecrash.reports.get</code></p>
<p><code>firebasecrashlytics.config.get</code></p>
<p><code>firebasecrashlytics.data.get</code></p>
<p><code>firebasecrashlytics.issues.get</code></p>
<p><code>firebasecrashlytics. issues. list</code></p>
<p><code>firebasecrashlytics. sessions. get</code></p>
<p><code>firebasedatabase.instances.get</code></p>
<p><code>firebasedatabase. instances. list</code></p>
<p><code>firebasedataconnect. connectorRevisions. get</code></p>
<p><code>firebasedataconnect. connectorRevisions. list</code></p>
<p><code>firebasedataconnect. connectors. get</code></p>
<p><code>firebasedataconnect. connectors. list</code></p>
<p><code>firebasedataconnect. locations.*</code></p>
<ul>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
</ul>
<p><code>firebasedataconnect. operations. get</code></p>
<p><code>firebasedataconnect. operations. list</code></p>
<p><code>firebasedataconnect. schemaRevisions. get</code></p>
<p><code>firebasedataconnect. schemaRevisions. list</code></p>
<p><code>firebasedataconnect. schemas. get</code></p>
<p><code>firebasedataconnect. schemas. list</code></p>
<p><code>firebasedataconnect. services. generateQuery</code></p>
<p><code>firebasedataconnect. services. generateSchema</code></p>
<p><code>firebasedataconnect. services. get</code></p>
<p><code>firebasedataconnect. services. introspectGraphql</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebasedynamiclinks. destinations. list</code></p>
<p><code>firebasedynamiclinks. domains. get</code></p>
<p><code>firebasedynamiclinks. domains. list</code></p>
<p><code>firebasedynamiclinks.links.get</code></p>
<p><code>firebasedynamiclinks. links. list</code></p>
<p><code>firebasedynamiclinks.stats.get</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseextensionspublisher. extensions. get</code></p>
<p><code>firebaseextensionspublisher. extensions. list</code></p>
<p><code>firebasehosting.sites.get</code></p>
<p><code>firebasehosting.sites.list</code></p>
<p><code>firebaseinappmessaging. campaigns. get</code></p>
<p><code>firebaseinappmessaging. campaigns. list</code></p>
<p><code>firebasemessagingcampaigns. campaigns. get</code></p>
<p><code>firebasemessagingcampaigns. campaigns. list</code></p>
<p><code>firebaseml.models.get</code></p>
<p><code>firebaseml.models.list</code></p>
<p><code>firebaseml.modelversions.get</code></p>
<p><code>firebaseml.modelversions.list</code></p>
<p><code>firebasenotifications. messages. get</code></p>
<p><code>firebasenotifications. messages. list</code></p>
<p><code>firebaseperformance.data.get</code></p>
<p><code>firebaserules.releases.get</code></p>
<p><code>firebaserules. releases. getExecutable</code></p>
<p><code>firebaserules.releases.list</code></p>
<p><code>firebaserules.rulesets.get</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>firebasestorage.buckets.get</code></p>
<p><code>firebasestorage.buckets.list</code></p>
<p><code>firebasestorage. defaultBucket. get</code></p>
<p><code>firebasevertexai.configs.get</code></p>
<p><code>firebasevertexai. promptTemplates. get</code></p>
<p><code>firebasevertexai. promptTemplates. list</code></p>
<p><code>logging.logEntries.download</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.views.access</code></p>
<p><code>logging.views.listLogs</code></p>
<p><code>logging.views.listResourceKeys</code></p>
<p><code>logging. views. listResourceValues</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>oauthconfig.verification.get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. runServiceCostInsights. get</code></p>
<p><code>recommender. runServiceCostInsights. list</code></p>
<p><code>recommender. runServiceCostRecommendations. get</code></p>
<p><code>recommender. runServiceCostRecommendations. list</code></p>
<p><code>recommender. runServiceIdentityInsights. get</code></p>
<p><code>recommender. runServiceIdentityInsights. list</code></p>
<p><code>recommender. runServiceIdentityRecommendations. get</code></p>
<p><code>recommender. runServiceIdentityRecommendations. list</code></p>
<p><code>recommender. runServicePerformanceInsights. get</code></p>
<p><code>recommender. runServicePerformanceInsights. list</code></p>
<p><code>recommender. runServicePerformanceRecommendations. get</code></p>
<p><code>recommender. runServicePerformanceRecommendations. list</code></p>
<p><code>recommender. runServiceSecurityInsights. get</code></p>
<p><code>recommender. runServiceSecurityInsights. list</code></p>
<p><code>recommender. runServiceSecurityRecommendations. get</code></p>
<p><code>recommender. runServiceSecurityRecommendations. list</code></p>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.configurations.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
</ul>
<p><code>run.executions.get</code></p>
<p><code>run.executions.list</code></p>
<p><code>run.instances.get</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.locations.list</code></p>
<p><code>run.operations.get</code></p>
<p><code>run.operations.list</code></p>
<p><code>run.prompts.get</code></p>
<p><code>run.revisions.get</code></p>
<p><code>run.revisions.list</code></p>
<p><code>run.routes.get</code></p>
<p><code>run.routes.list</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>run.tasks.*</code></p>
<ul>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
</ul>
<p><code>run.workerpools.get</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Analytics Admin
<p>( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p>Full access to Google Analytics for Firebase.</p></td>
<td><p><code>cloudnotifications. activities. list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseanalytics.*</code></p>
<ul>
<li><code>firebaseanalytics. resources. googleAnalyticsEdit</code></li>
<li><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Analytics Viewer
<p>( <code>roles/ firebase.analyticsViewer</code> )</p>
<p>Read access to Google Analytics for Firebase.</p></td>
<td><p><code>cloudnotifications. activities. list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Develop Admin
<p>( <code>roles/ firebase.developAdmin</code> )</p>
<p>Full access to Firebase Develop products and Analytics.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.getKeyString</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>apikeys.keys.lookup</code></p>
<p><code>appengine.applications.get</code></p>
<p><code>artifactregistry. attachments. get</code></p>
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
<p><code>automl.*</code></p>
<ul>
<li><code>automl.annotationSpecs.create</code></li>
<li><code>automl.annotationSpecs.delete</code></li>
<li><code>automl.annotationSpecs.get</code></li>
<li><code>automl.annotationSpecs.list</code></li>
<li><code>automl.annotationSpecs.update</code></li>
<li><code>automl.annotations.approve</code></li>
<li><code>automl.annotations.create</code></li>
<li><code>automl.annotations.list</code></li>
<li><code>automl.annotations.manipulate</code></li>
<li><code>automl.annotations.reject</code></li>
<li><code>automl.columnSpecs.get</code></li>
<li><code>automl.columnSpecs.list</code></li>
<li><code>automl.columnSpecs.update</code></li>
<li><code>automl.datasets.create</code></li>
<li><code>automl.datasets.delete</code></li>
<li><code>automl.datasets.export</code></li>
<li><code>automl.datasets.get</code></li>
<li><code>automl.datasets.getIamPolicy</code></li>
<li><code>automl.datasets.import</code></li>
<li><code>automl.datasets.list</code></li>
<li><code>automl.datasets.setIamPolicy</code></li>
<li><code>automl.datasets.update</code></li>
<li><code>automl.examples.delete</code></li>
<li><code>automl.examples.get</code></li>
<li><code>automl.examples.list</code></li>
<li><code>automl.examples.update</code></li>
<li><code>automl.files.delete</code></li>
<li><code>automl.files.list</code></li>
<li><code>automl. humanAnnotationTasks. create</code></li>
<li><code>automl. humanAnnotationTasks. delete</code></li>
<li><code>automl. humanAnnotationTasks. get</code></li>
<li><code>automl. humanAnnotationTasks. list</code></li>
<li><code>automl.locations.get</code></li>
<li><code>automl.locations.getIamPolicy</code></li>
<li><code>automl.locations.list</code></li>
<li><code>automl.locations.setIamPolicy</code></li>
<li><code>automl.modelEvaluations.create</code></li>
<li><code>automl.modelEvaluations.get</code></li>
<li><code>automl.modelEvaluations.list</code></li>
<li><code>automl.models.create</code></li>
<li><code>automl.models.delete</code></li>
<li><code>automl.models.deploy</code></li>
<li><code>automl.models.export</code></li>
<li><code>automl.models.get</code></li>
<li><code>automl.models.getIamPolicy</code></li>
<li><code>automl.models.list</code></li>
<li><code>automl.models.predict</code></li>
<li><code>automl.models.setIamPolicy</code></li>
<li><code>automl.models.undeploy</code></li>
<li><code>automl.operations.cancel</code></li>
<li><code>automl.operations.delete</code></li>
<li><code>automl.operations.get</code></li>
<li><code>automl.operations.list</code></li>
<li><code>automl.tableSpecs.get</code></li>
<li><code>automl.tableSpecs.list</code></li>
<li><code>automl.tableSpecs.update</code></li>
</ul>
<p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig.brands.update</code></p>
<p><code>clientauthconfig.clients.get</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudfunctions.*</code></p>
<ul>
<li><code>cloudfunctions.functions.call</code></li>
<li><code>cloudfunctions. functions. create</code></li>
<li><code>cloudfunctions. functions. delete</code></li>
<li><code>cloudfunctions. functions. generationUpgrade</code></li>
<li><code>cloudfunctions.functions.get</code></li>
<li><code>cloudfunctions. functions. getIamPolicy</code></li>
<li><code>cloudfunctions. functions. invoke</code></li>
<li><code>cloudfunctions.functions.list</code></li>
<li><code>cloudfunctions. functions. setIamPolicy</code></li>
<li><code>cloudfunctions. functions. sourceCodeGet</code></li>
<li><code>cloudfunctions. functions. sourceCodeSet</code></li>
<li><code>cloudfunctions. functions. update</code></li>
<li><code>cloudfunctions.locations.list</code></li>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries.*</code></p>
<ul>
<li><code>databasesconsole. studioQueries. create</code></li>
<li><code>databasesconsole. studioQueries. delete</code></li>
<li><code>databasesconsole. studioQueries. get</code></li>
<li><code>databasesconsole. studioQueries. list</code></li>
<li><code>databasesconsole. studioQueries. search</code></li>
<li><code>databasesconsole. studioQueries. update</code></li>
</ul>
<p><code>datastore.*</code></p>
<ul>
<li><code>datastore. backupSchedules. create</code></li>
<li><code>datastore. backupSchedules. delete</code></li>
<li><code>datastore.backupSchedules.get</code></li>
<li><code>datastore.backupSchedules.list</code></li>
<li><code>datastore. backupSchedules. update</code></li>
<li><code>datastore.backups.delete</code></li>
<li><code>datastore.backups.get</code></li>
<li><code>datastore.backups.list</code></li>
<li><code>datastore. backups. restoreDatabase</code></li>
<li><code>datastore.databases.bulkDelete</code></li>
<li><code>datastore.databases.clone</code></li>
<li><code>datastore.databases.create</code></li>
<li><code>datastore. databases. createTagBinding</code></li>
<li><code>datastore.databases.delete</code></li>
<li><code>datastore. databases. deleteTagBinding</code></li>
<li><code>datastore.databases.export</code></li>
<li><code>datastore.databases.get</code></li>
<li><code>datastore. databases. getMetadata</code></li>
<li><code>datastore.databases.import</code></li>
<li><code>datastore.databases.list</code></li>
<li><code>datastore. databases. listEffectiveTags</code></li>
<li><code>datastore. databases. listTagBindings</code></li>
<li><code>datastore.databases.update</code></li>
<li><code>datastore.entities.allocateIds</code></li>
<li><code>datastore.entities.create</code></li>
<li><code>datastore.entities.delete</code></li>
<li><code>datastore.entities.get</code></li>
<li><code>datastore.entities.list</code></li>
<li><code>datastore.entities.update</code></li>
<li><code>datastore.insights.get</code></li>
<li><code>datastore. keyVisualizerScans. get</code></li>
<li><code>datastore. keyVisualizerScans. list</code></li>
<li><code>datastore.locations.get</code></li>
<li><code>datastore.locations.list</code></li>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
<li><code>datastore.operations.cancel</code></li>
<li><code>datastore.operations.delete</code></li>
<li><code>datastore.operations.get</code></li>
<li><code>datastore.operations.list</code></li>
<li><code>datastore.schemas.create</code></li>
<li><code>datastore.schemas.delete</code></li>
<li><code>datastore.schemas.get</code></li>
<li><code>datastore.schemas.list</code></li>
<li><code>datastore.schemas.update</code></li>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
<li><code>datastore.userCreds.create</code></li>
<li><code>datastore.userCreds.delete</code></li>
<li><code>datastore.userCreds.get</code></li>
<li><code>datastore.userCreds.list</code></li>
<li><code>datastore.userCreds.update</code></li>
</ul>
<p><code>errorreporting.groups.list</code></p>
<p><code>eventarc.*</code></p>
<ul>
<li><code>eventarc. channelConnections. create</code></li>
<li><code>eventarc. channelConnections. createTagBinding</code></li>
<li><code>eventarc. channelConnections. delete</code></li>
<li><code>eventarc. channelConnections. deleteTagBinding</code></li>
<li><code>eventarc. channelConnections. get</code></li>
<li><code>eventarc. channelConnections. getIamPolicy</code></li>
<li><code>eventarc. channelConnections. list</code></li>
<li><code>eventarc. channelConnections. listEffectiveTags</code></li>
<li><code>eventarc. channelConnections. listTagBindings</code></li>
<li><code>eventarc. channelConnections. publish</code></li>
<li><code>eventarc. channelConnections. setIamPolicy</code></li>
<li><code>eventarc.channels.attach</code></li>
<li><code>eventarc.channels.create</code></li>
<li><code>eventarc. channels. createTagBinding</code></li>
<li><code>eventarc.channels.delete</code></li>
<li><code>eventarc. channels. deleteTagBinding</code></li>
<li><code>eventarc.channels.get</code></li>
<li><code>eventarc.channels.getIamPolicy</code></li>
<li><code>eventarc.channels.list</code></li>
<li><code>eventarc. channels. listEffectiveTags</code></li>
<li><code>eventarc. channels. listTagBindings</code></li>
<li><code>eventarc.channels.publish</code></li>
<li><code>eventarc.channels.setIamPolicy</code></li>
<li><code>eventarc.channels.undelete</code></li>
<li><code>eventarc.channels.update</code></li>
<li><code>eventarc.enrollments.create</code></li>
<li><code>eventarc.enrollments.delete</code></li>
<li><code>eventarc.enrollments.get</code></li>
<li><code>eventarc. enrollments. getIamPolicy</code></li>
<li><code>eventarc.enrollments.list</code></li>
<li><code>eventarc. enrollments. setIamPolicy</code></li>
<li><code>eventarc.enrollments.update</code></li>
<li><code>eventarc. events. receiveAuditLogWritten</code></li>
<li><code>eventarc.events.receiveEvent</code></li>
<li><code>eventarc. googleApiSources. create</code></li>
<li><code>eventarc. googleApiSources. delete</code></li>
<li><code>eventarc.googleApiSources.get</code></li>
<li><code>eventarc. googleApiSources. getIamPolicy</code></li>
<li><code>eventarc.googleApiSources.list</code></li>
<li><code>eventarc. googleApiSources. setIamPolicy</code></li>
<li><code>eventarc. googleApiSources. update</code></li>
<li><code>eventarc. googleChannelConfigs. get</code></li>
<li><code>eventarc. googleChannelConfigs. update</code></li>
<li><code>eventarc.kafkaSources.create</code></li>
<li><code>eventarc.kafkaSources.delete</code></li>
<li><code>eventarc.kafkaSources.get</code></li>
<li><code>eventarc. kafkaSources. getIamPolicy</code></li>
<li><code>eventarc.kafkaSources.list</code></li>
<li><code>eventarc. kafkaSources. setIamPolicy</code></li>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
<li><code>eventarc.messageBuses.create</code></li>
<li><code>eventarc.messageBuses.delete</code></li>
<li><code>eventarc.messageBuses.get</code></li>
<li><code>eventarc. messageBuses. getIamPolicy</code></li>
<li><code>eventarc.messageBuses.list</code></li>
<li><code>eventarc.messageBuses.publish</code></li>
<li><code>eventarc. messageBuses. setIamPolicy</code></li>
<li><code>eventarc.messageBuses.update</code></li>
<li><code>eventarc.messageBuses.use</code></li>
<li><code>eventarc. multiProjectSources. collectGoogleApiEvents</code></li>
<li><code>eventarc.operations.cancel</code></li>
<li><code>eventarc.operations.delete</code></li>
<li><code>eventarc.operations.get</code></li>
<li><code>eventarc.operations.list</code></li>
<li><code>eventarc.pipelines.create</code></li>
<li><code>eventarc.pipelines.delete</code></li>
<li><code>eventarc.pipelines.get</code></li>
<li><code>eventarc. pipelines. getIamPolicy</code></li>
<li><code>eventarc.pipelines.list</code></li>
<li><code>eventarc. pipelines. setIamPolicy</code></li>
<li><code>eventarc.pipelines.update</code></li>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
<li><code>eventarc.triggers.create</code></li>
<li><code>eventarc. triggers. createTagBinding</code></li>
<li><code>eventarc.triggers.delete</code></li>
<li><code>eventarc. triggers. deleteTagBinding</code></li>
<li><code>eventarc.triggers.get</code></li>
<li><code>eventarc.triggers.getIamPolicy</code></li>
<li><code>eventarc.triggers.list</code></li>
<li><code>eventarc. triggers. listEffectiveTags</code></li>
<li><code>eventarc. triggers. listTagBindings</code></li>
<li><code>eventarc.triggers.setIamPolicy</code></li>
<li><code>eventarc.triggers.undelete</code></li>
<li><code>eventarc.triggers.update</code></li>
</ul>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseanalytics.*</code></p>
<ul>
<li><code>firebaseanalytics. resources. googleAnalyticsEdit</code></li>
<li><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code>firebaseappcheck.*</code></p>
<ul>
<li><code>firebaseappcheck. appAttestConfig. get</code></li>
<li><code>firebaseappcheck. appAttestConfig. update</code></li>
<li><code>firebaseappcheck. appCheckTokens. verify</code></li>
<li><code>firebaseappcheck. automations. create</code></li>
<li><code>firebaseappcheck. automations. delete</code></li>
<li><code>firebaseappcheck. automations. get</code></li>
<li><code>firebaseappcheck. automations. list</code></li>
<li><code>firebaseappcheck. automations. resume</code></li>
<li><code>firebaseappcheck. automations. suspend</code></li>
<li><code>firebaseappcheck. automations. update</code></li>
<li><code>firebaseappcheck. debugTokens. get</code></li>
<li><code>firebaseappcheck. debugTokens. update</code></li>
<li><code>firebaseappcheck. deviceCheckConfig. get</code></li>
<li><code>firebaseappcheck. deviceCheckConfig. update</code></li>
<li><code>firebaseappcheck. playIntegrityConfig. get</code></li>
<li><code>firebaseappcheck. playIntegrityConfig. update</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. update</code></li>
<li><code>firebaseappcheck. recaptchaV3Config. get</code></li>
<li><code>firebaseappcheck. recaptchaV3Config. update</code></li>
<li><code>firebaseappcheck. resourcePolicies. get</code></li>
<li><code>firebaseappcheck. resourcePolicies. update</code></li>
<li><code>firebaseappcheck. safetyNetConfig. get</code></li>
<li><code>firebaseappcheck. safetyNetConfig. update</code></li>
<li><code>firebaseappcheck.services.get</code></li>
<li><code>firebaseappcheck. services. update</code></li>
<li><code>firebaseappcheck.tokens.mint</code></li>
</ul>
<p><code>firebaseapphosting.*</code></p>
<ul>
<li><code>firebaseapphosting. backends. create</code></li>
<li><code>firebaseapphosting. backends. delete</code></li>
<li><code>firebaseapphosting. backends. get</code></li>
<li><code>firebaseapphosting. backends. list</code></li>
<li><code>firebaseapphosting. backends. update</code></li>
<li><code>firebaseapphosting. builds. create</code></li>
<li><code>firebaseapphosting. builds. delete</code></li>
<li><code>firebaseapphosting.builds.get</code></li>
<li><code>firebaseapphosting.builds.list</code></li>
<li><code>firebaseapphosting. builds. update</code></li>
<li><code>firebaseapphosting. domains. create</code></li>
<li><code>firebaseapphosting. domains. delete</code></li>
<li><code>firebaseapphosting.domains.get</code></li>
<li><code>firebaseapphosting. domains. list</code></li>
<li><code>firebaseapphosting. domains. update</code></li>
<li><code>firebaseapphosting. locations. get</code></li>
<li><code>firebaseapphosting. locations. list</code></li>
<li><code>firebaseapphosting. operations. cancel</code></li>
<li><code>firebaseapphosting. operations. delete</code></li>
<li><code>firebaseapphosting. operations. get</code></li>
<li><code>firebaseapphosting. operations. list</code></li>
<li><code>firebaseapphosting. rollouts. create</code></li>
<li><code>firebaseapphosting. rollouts. delete</code></li>
<li><code>firebaseapphosting. rollouts. get</code></li>
<li><code>firebaseapphosting. rollouts. list</code></li>
<li><code>firebaseapphosting. rollouts. update</code></li>
<li><code>firebaseapphosting.traffic.get</code></li>
<li><code>firebaseapphosting. traffic. update</code></li>
</ul>
<p><code>firebaseauth.*</code></p>
<ul>
<li><code>firebaseauth.configs.create</code></li>
<li><code>firebaseauth.configs.get</code></li>
<li><code>firebaseauth. configs. getHashConfig</code></li>
<li><code>firebaseauth.configs.getSecret</code></li>
<li><code>firebaseauth.configs.update</code></li>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>firebasedatabase.*</code></p>
<ul>
<li><code>firebasedatabase. instances. create</code></li>
<li><code>firebasedatabase. instances. delete</code></li>
<li><code>firebasedatabase. instances. disable</code></li>
<li><code>firebasedatabase.instances.get</code></li>
<li><code>firebasedatabase. instances. list</code></li>
<li><code>firebasedatabase. instances. reenable</code></li>
<li><code>firebasedatabase. instances. undelete</code></li>
<li><code>firebasedatabase. instances. update</code></li>
</ul>
<p><code>firebasedataconnect.*</code></p>
<ul>
<li><code>firebasedataconnect. connectorRevisions. delete</code></li>
<li><code>firebasedataconnect. connectorRevisions. get</code></li>
<li><code>firebasedataconnect. connectorRevisions. list</code></li>
<li><code>firebasedataconnect. connectors. create</code></li>
<li><code>firebasedataconnect. connectors. delete</code></li>
<li><code>firebasedataconnect. connectors. get</code></li>
<li><code>firebasedataconnect. connectors. impersonateMutation</code></li>
<li><code>firebasedataconnect. connectors. impersonateQuery</code></li>
<li><code>firebasedataconnect. connectors. list</code></li>
<li><code>firebasedataconnect. connectors. update</code></li>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
<li><code>firebasedataconnect. operations. cancel</code></li>
<li><code>firebasedataconnect. operations. delete</code></li>
<li><code>firebasedataconnect. operations. get</code></li>
<li><code>firebasedataconnect. operations. list</code></li>
<li><code>firebasedataconnect. schemaRevisions. delete</code></li>
<li><code>firebasedataconnect. schemaRevisions. get</code></li>
<li><code>firebasedataconnect. schemaRevisions. list</code></li>
<li><code>firebasedataconnect. schemas. create</code></li>
<li><code>firebasedataconnect. schemas. delete</code></li>
<li><code>firebasedataconnect. schemas. get</code></li>
<li><code>firebasedataconnect. schemas. list</code></li>
<li><code>firebasedataconnect. schemas. migrate</code></li>
<li><code>firebasedataconnect. schemas. update</code></li>
<li><code>firebasedataconnect. services. create</code></li>
<li><code>firebasedataconnect. services. delete</code></li>
<li><code>firebasedataconnect. services. executeGraphql</code></li>
<li><code>firebasedataconnect. services. executeGraphqlRead</code></li>
<li><code>firebasedataconnect. services. generateQuery</code></li>
<li><code>firebasedataconnect. services. generateSchema</code></li>
<li><code>firebasedataconnect. services. get</code></li>
<li><code>firebasedataconnect. services. introspectGraphql</code></li>
<li><code>firebasedataconnect. services. list</code></li>
<li><code>firebasedataconnect. services. update</code></li>
</ul>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebasehosting.*</code></p>
<ul>
<li><code>firebasehosting.sites.create</code></li>
<li><code>firebasehosting.sites.delete</code></li>
<li><code>firebasehosting.sites.get</code></li>
<li><code>firebasehosting.sites.list</code></li>
<li><code>firebasehosting.sites.update</code></li>
</ul>
<p><code>firebaseml.*</code></p>
<ul>
<li><code>firebaseml.models.create</code></li>
<li><code>firebaseml.models.delete</code></li>
<li><code>firebaseml.models.get</code></li>
<li><code>firebaseml.models.list</code></li>
<li><code>firebaseml.models.update</code></li>
<li><code>firebaseml. modelversions. create</code></li>
<li><code>firebaseml.modelversions.get</code></li>
<li><code>firebaseml.modelversions.list</code></li>
<li><code>firebaseml. modelversions. update</code></li>
</ul>
<p><code>firebaserules.*</code></p>
<ul>
<li><code>firebaserules.releases.create</code></li>
<li><code>firebaserules.releases.delete</code></li>
<li><code>firebaserules.releases.get</code></li>
<li><code>firebaserules. releases. getExecutable</code></li>
<li><code>firebaserules.releases.list</code></li>
<li><code>firebaserules.releases.update</code></li>
<li><code>firebaserules.rulesets.create</code></li>
<li><code>firebaserules.rulesets.delete</code></li>
<li><code>firebaserules.rulesets.get</code></li>
<li><code>firebaserules.rulesets.list</code></li>
<li><code>firebaserules.rulesets.test</code></li>
</ul>
<p><code>firebasestorage.*</code></p>
<ul>
<li><code>firebasestorage. buckets. addFirebase</code></li>
<li><code>firebasestorage.buckets.get</code></li>
<li><code>firebasestorage.buckets.list</code></li>
<li><code>firebasestorage. buckets. removeFirebase</code></li>
<li><code>firebasestorage. defaultBucket. create</code></li>
<li><code>firebasestorage. defaultBucket. delete</code></li>
<li><code>firebasestorage. defaultBucket. get</code></li>
</ul>
<p><code>firebasevertexai.*</code></p>
<ul>
<li><code>firebasevertexai.configs.get</code></li>
<li><code>firebasevertexai. configs. update</code></li>
<li><code>firebasevertexai. promptTemplates. create</code></li>
<li><code>firebasevertexai. promptTemplates. delete</code></li>
<li><code>firebasevertexai. promptTemplates. get</code></li>
<li><code>firebasevertexai. promptTemplates. list</code></li>
<li><code>firebasevertexai. promptTemplates. update</code></li>
<li><code>firebasevertexai. promptTemplates. updateLock</code></li>
</ul>
<p><code>logging.logEntries.list</code></p>
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
<p><code>oauthconfig.verification.get</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights.*</code></p>
<ul>
<li><code>recommender. cloudFunctionsPerformanceInsights. get</code></li>
<li><code>recommender. cloudFunctionsPerformanceInsights. list</code></li>
<li><code>recommender. cloudFunctionsPerformanceInsights. update</code></li>
</ul>
<p><code>recommender. cloudFunctionsPerformanceRecommendations.*</code></p>
<ul>
<li><code>recommender. cloudFunctionsPerformanceRecommendations. get</code></li>
<li><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></li>
<li><code>recommender. cloudFunctionsPerformanceRecommendations. update</code></li>
</ul>
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
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. runServiceCostInsights.*</code></p>
<ul>
<li><code>recommender. runServiceCostInsights. get</code></li>
<li><code>recommender. runServiceCostInsights. list</code></li>
<li><code>recommender. runServiceCostInsights. update</code></li>
</ul>
<p><code>recommender. runServiceCostRecommendations.*</code></p>
<ul>
<li><code>recommender. runServiceCostRecommendations. get</code></li>
<li><code>recommender. runServiceCostRecommendations. list</code></li>
<li><code>recommender. runServiceCostRecommendations. update</code></li>
</ul>
<p><code>recommender. runServiceIdentityInsights.*</code></p>
<ul>
<li><code>recommender. runServiceIdentityInsights. get</code></li>
<li><code>recommender. runServiceIdentityInsights. list</code></li>
<li><code>recommender. runServiceIdentityInsights. update</code></li>
</ul>
<p><code>recommender. runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code>recommender. runServiceIdentityRecommendations. get</code></li>
<li><code>recommender. runServiceIdentityRecommendations. list</code></li>
<li><code>recommender. runServiceIdentityRecommendations. update</code></li>
</ul>
<p><code>recommender. runServicePerformanceInsights.*</code></p>
<ul>
<li><code>recommender. runServicePerformanceInsights. get</code></li>
<li><code>recommender. runServicePerformanceInsights. list</code></li>
<li><code>recommender. runServicePerformanceInsights. update</code></li>
</ul>
<p><code>recommender. runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code>recommender. runServicePerformanceRecommendations. get</code></li>
<li><code>recommender. runServicePerformanceRecommendations. list</code></li>
<li><code>recommender. runServicePerformanceRecommendations. update</code></li>
</ul>
<p><code>recommender. runServiceSecurityInsights.*</code></p>
<ul>
<li><code>recommender. runServiceSecurityInsights. get</code></li>
<li><code>recommender. runServiceSecurityInsights. list</code></li>
<li><code>recommender. runServiceSecurityInsights. update</code></li>
</ul>
<p><code>recommender. runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code>recommender. runServiceSecurityRecommendations. get</code></li>
<li><code>recommender. runServiceSecurityRecommendations. list</code></li>
<li><code>recommender. runServiceSecurityRecommendations. update</code></li>
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
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
<li><code>run.executions.cancel</code></li>
<li><code>run.executions.delete</code></li>
<li><code>run.executions.get</code></li>
<li><code>run.executions.list</code></li>
<li><code>run.instances.create</code></li>
<li><code>run.instances.delete</code></li>
<li><code>run.instances.get</code></li>
<li><code>run.instances.getIamPolicy</code></li>
<li><code>run.instances.invoke</code></li>
<li><code>run.instances.list</code></li>
<li><code>run.instances.setIamPolicy</code></li>
<li><code>run.instances.sshRead</code></li>
<li><code>run.instances.sshRoot</code></li>
<li><code>run.instances.start</code></li>
<li><code>run.instances.stop</code></li>
<li><code>run.instances.update</code></li>
<li><code>run.jobs.create</code></li>
<li><code>run.jobs.createTagBinding</code></li>
<li><code>run.jobs.delete</code></li>
<li><code>run.jobs.deleteTagBinding</code></li>
<li><code>run.jobs.get</code></li>
<li><code>run.jobs.getIamPolicy</code></li>
<li><code>run.jobs.list</code></li>
<li><code>run.jobs.listEffectiveTags</code></li>
<li><code>run.jobs.listTagBindings</code></li>
<li><code>run.jobs.run</code></li>
<li><code>run.jobs.runWithOverrides</code></li>
<li><code>run.jobs.setIamPolicy</code></li>
<li><code>run.jobs.sshRead</code></li>
<li><code>run.jobs.sshRoot</code></li>
<li><code>run.jobs.update</code></li>
<li><code>run.locations.list</code></li>
<li><code>run.locations.uploadSource</code></li>
<li><code>run.operations.delete</code></li>
<li><code>run.operations.get</code></li>
<li><code>run.operations.list</code></li>
<li><code>run.prompts.get</code></li>
<li><code>run.revisions.delete</code></li>
<li><code>run.revisions.get</code></li>
<li><code>run.revisions.list</code></li>
<li><code>run.routes.get</code></li>
<li><code>run.routes.invoke</code></li>
<li><code>run.routes.list</code></li>
<li><code>run.services.create</code></li>
<li><code>run.services.createTagBinding</code></li>
<li><code>run.services.delete</code></li>
<li><code>run.services.deleteTagBinding</code></li>
<li><code>run.services.get</code></li>
<li><code>run.services.getIamPolicy</code></li>
<li><code>run.services.list</code></li>
<li><code>run.services.listEffectiveTags</code></li>
<li><code>run.services.listTagBindings</code></li>
<li><code>run.services.setIamPolicy</code></li>
<li><code>run.services.sshRead</code></li>
<li><code>run.services.sshRoot</code></li>
<li><code>run.services.update</code></li>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
<li><code>run.workerpools.create</code></li>
<li><code>run.workerpools.delete</code></li>
<li><code>run.workerpools.get</code></li>
<li><code>run.workerpools.getIamPolicy</code></li>
<li><code>run.workerpools.list</code></li>
<li><code>run.workerpools.setIamPolicy</code></li>
<li><code>run.workerpools.sshRead</code></li>
<li><code>run.workerpools.sshRoot</code></li>
<li><code>run.workerpools.update</code></li>
</ul>
<p><code>runtimeconfig.configs.create</code></p>
<p><code>runtimeconfig.configs.delete</code></p>
<p><code>runtimeconfig.configs.get</code></p>
<p><code>runtimeconfig.configs.list</code></p>
<p><code>runtimeconfig.configs.update</code></p>
<p><code>runtimeconfig.operations.*</code></p>
<ul>
<li><code>runtimeconfig.operations.get</code></li>
<li><code>runtimeconfig.operations.list</code></li>
</ul>
<p><code>runtimeconfig.variables.create</code></p>
<p><code>runtimeconfig.variables.delete</code></p>
<p><code>runtimeconfig.variables.get</code></p>
<p><code>runtimeconfig.variables.list</code></p>
<p><code>runtimeconfig.variables.update</code></p>
<p><code>runtimeconfig.variables.watch</code></p>
<p><code>runtimeconfig.waiters.create</code></p>
<p><code>runtimeconfig.waiters.delete</code></p>
<p><code>runtimeconfig.waiters.get</code></p>
<p><code>runtimeconfig.waiters.list</code></p>
<p><code>runtimeconfig.waiters.update</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
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
<tr class="odd">
<td>Firebase Develop Viewer
<p>( <code>roles/ firebase.developViewer</code> )</p>
<p>Read access to Firebase Develop products and Analytics.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>automl.annotationSpecs.get</code></p>
<p><code>automl.annotationSpecs.list</code></p>
<p><code>automl.annotations.list</code></p>
<p><code>automl.columnSpecs.get</code></p>
<p><code>automl.columnSpecs.list</code></p>
<p><code>automl.datasets.get</code></p>
<p><code>automl.datasets.list</code></p>
<p><code>automl.examples.get</code></p>
<p><code>automl.examples.list</code></p>
<p><code>automl.files.list</code></p>
<p><code>automl. humanAnnotationTasks. get</code></p>
<p><code>automl. humanAnnotationTasks. list</code></p>
<p><code>automl.locations.get</code></p>
<p><code>automl.locations.list</code></p>
<p><code>automl.modelEvaluations.get</code></p>
<p><code>automl.modelEvaluations.list</code></p>
<p><code>automl.models.get</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.operations.get</code></p>
<p><code>automl.operations.list</code></p>
<p><code>automl.tableSpecs.get</code></p>
<p><code>automl.tableSpecs.list</code></p>
<p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.*</code></p>
<ul>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>datastore.backups.get</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.entities.get</code></p>
<p><code>datastore.entities.list</code></p>
<p><code>datastore.namespaces.*</code></p>
<ul>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
</ul>
<p><code>datastore.schemas.get</code></p>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.*</code></p>
<ul>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
</ul>
<p><code>datastore.userCreds.get</code></p>
<p><code>datastore.userCreds.list</code></p>
<p><code>errorreporting.groups.list</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc.enrollments.get</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.googleApiSources.get</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleChannelConfigs. get</code></p>
<p><code>eventarc.kafkaSources.get</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc.locations.*</code></p>
<ul>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
</ul>
<p><code>eventarc.messageBuses.get</code></p>
<p><code>eventarc. messageBuses. getIamPolicy</code></p>
<p><code>eventarc.messageBuses.list</code></p>
<p><code>eventarc.messageBuses.use</code></p>
<p><code>eventarc. multiProjectSources. collectGoogleApiEvents</code></p>
<p><code>eventarc.operations.get</code></p>
<p><code>eventarc.operations.list</code></p>
<p><code>eventarc.pipelines.get</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.providers.*</code></p>
<ul>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
</ul>
<p><code>eventarc.triggers.get</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></p>
<p><code>firebaseappcheck. appAttestConfig. get</code></p>
<p><code>firebaseappcheck. automations. get</code></p>
<p><code>firebaseappcheck. automations. list</code></p>
<p><code>firebaseappcheck. debugTokens. get</code></p>
<p><code>firebaseappcheck. deviceCheckConfig. get</code></p>
<p><code>firebaseappcheck. playIntegrityConfig. get</code></p>
<p><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></p>
<p><code>firebaseappcheck. recaptchaV3Config. get</code></p>
<p><code>firebaseappcheck. resourcePolicies. get</code></p>
<p><code>firebaseappcheck. safetyNetConfig. get</code></p>
<p><code>firebaseappcheck.services.get</code></p>
<p><code>firebaseapphosting. backends. get</code></p>
<p><code>firebaseapphosting. backends. list</code></p>
<p><code>firebaseapphosting.builds.get</code></p>
<p><code>firebaseapphosting.builds.list</code></p>
<p><code>firebaseapphosting.domains.get</code></p>
<p><code>firebaseapphosting. domains. list</code></p>
<p><code>firebaseapphosting.locations.*</code></p>
<ul>
<li><code>firebaseapphosting. locations. get</code></li>
<li><code>firebaseapphosting. locations. list</code></li>
</ul>
<p><code>firebaseapphosting. operations. get</code></p>
<p><code>firebaseapphosting. operations. list</code></p>
<p><code>firebaseapphosting. rollouts. get</code></p>
<p><code>firebaseapphosting. rollouts. list</code></p>
<p><code>firebaseapphosting.traffic.get</code></p>
<p><code>firebaseauth.configs.get</code></p>
<p><code>firebaseauth.users.get</code></p>
<p><code>firebasedatabase.instances.get</code></p>
<p><code>firebasedatabase. instances. list</code></p>
<p><code>firebasedataconnect. connectorRevisions. get</code></p>
<p><code>firebasedataconnect. connectorRevisions. list</code></p>
<p><code>firebasedataconnect. connectors. get</code></p>
<p><code>firebasedataconnect. connectors. list</code></p>
<p><code>firebasedataconnect. locations.*</code></p>
<ul>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
</ul>
<p><code>firebasedataconnect. operations. get</code></p>
<p><code>firebasedataconnect. operations. list</code></p>
<p><code>firebasedataconnect. schemaRevisions. get</code></p>
<p><code>firebasedataconnect. schemaRevisions. list</code></p>
<p><code>firebasedataconnect. schemas. get</code></p>
<p><code>firebasedataconnect. schemas. list</code></p>
<p><code>firebasedataconnect. services. generateQuery</code></p>
<p><code>firebasedataconnect. services. generateSchema</code></p>
<p><code>firebasedataconnect. services. get</code></p>
<p><code>firebasedataconnect. services. introspectGraphql</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebasehosting.sites.get</code></p>
<p><code>firebasehosting.sites.list</code></p>
<p><code>firebaseml.models.get</code></p>
<p><code>firebaseml.models.list</code></p>
<p><code>firebaseml.modelversions.get</code></p>
<p><code>firebaseml.modelversions.list</code></p>
<p><code>firebaserules.releases.get</code></p>
<p><code>firebaserules. releases. getExecutable</code></p>
<p><code>firebaserules.releases.list</code></p>
<p><code>firebaserules.rulesets.get</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>firebasestorage.buckets.get</code></p>
<p><code>firebasestorage.buckets.list</code></p>
<p><code>firebasestorage. defaultBucket. get</code></p>
<p><code>firebasevertexai.configs.get</code></p>
<p><code>firebasevertexai. promptTemplates. get</code></p>
<p><code>firebasevertexai. promptTemplates. list</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>oauthconfig.verification.get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. runServiceCostInsights. get</code></p>
<p><code>recommender. runServiceCostInsights. list</code></p>
<p><code>recommender. runServiceCostRecommendations. get</code></p>
<p><code>recommender. runServiceCostRecommendations. list</code></p>
<p><code>recommender. runServiceIdentityInsights. get</code></p>
<p><code>recommender. runServiceIdentityInsights. list</code></p>
<p><code>recommender. runServiceIdentityRecommendations. get</code></p>
<p><code>recommender. runServiceIdentityRecommendations. list</code></p>
<p><code>recommender. runServicePerformanceInsights. get</code></p>
<p><code>recommender. runServicePerformanceInsights. list</code></p>
<p><code>recommender. runServicePerformanceRecommendations. get</code></p>
<p><code>recommender. runServicePerformanceRecommendations. list</code></p>
<p><code>recommender. runServiceSecurityInsights. get</code></p>
<p><code>recommender. runServiceSecurityInsights. list</code></p>
<p><code>recommender. runServiceSecurityRecommendations. get</code></p>
<p><code>recommender. runServiceSecurityRecommendations. list</code></p>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.configurations.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
</ul>
<p><code>run.executions.get</code></p>
<p><code>run.executions.list</code></p>
<p><code>run.instances.get</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.locations.list</code></p>
<p><code>run.operations.get</code></p>
<p><code>run.operations.list</code></p>
<p><code>run.prompts.get</code></p>
<p><code>run.revisions.get</code></p>
<p><code>run.revisions.list</code></p>
<p><code>run.routes.get</code></p>
<p><code>run.routes.list</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>run.tasks.*</code></p>
<ul>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
</ul>
<p><code>run.workerpools.get</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Grow Admin
<p>( <code>roles/ firebase.growthAdmin</code> )</p>
<p>Full access to Firebase Grow products and Analytics.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>clientauthconfig.clients.get</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>cloudconfig.*</code></p>
<ul>
<li><code>cloudconfig.configs.get</code></li>
<li><code>cloudconfig.configs.update</code></li>
</ul>
<p><code>cloudmessaging.*</code></p>
<ul>
<li><code>cloudmessaging.messages.create</code></li>
<li><code>cloudmessaging. topicSubscriptions. create</code></li>
<li><code>cloudmessaging. topicSubscriptions. delete</code></li>
<li><code>cloudmessaging. topicSubscriptions. get</code></li>
<li><code>cloudmessaging. topicSubscriptions. list</code></li>
<li><code>cloudmessaging. topicSubscriptions. update</code></li>
</ul>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseabt.*</code></p>
<ul>
<li><code>firebaseabt. experimentresults. get</code></li>
<li><code>firebaseabt.experiments.create</code></li>
<li><code>firebaseabt.experiments.delete</code></li>
<li><code>firebaseabt.experiments.get</code></li>
<li><code>firebaseabt.experiments.list</code></li>
<li><code>firebaseabt.experiments.update</code></li>
<li><code>firebaseabt. projectmetadata. get</code></li>
</ul>
<p><code>firebaseanalytics.*</code></p>
<ul>
<li><code>firebaseanalytics. resources. googleAnalyticsEdit</code></li>
<li><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code>firebasedynamiclinks.*</code></p>
<ul>
<li><code>firebasedynamiclinks. destinations. list</code></li>
<li><code>firebasedynamiclinks. destinations. update</code></li>
<li><code>firebasedynamiclinks. domains. create</code></li>
<li><code>firebasedynamiclinks. domains. delete</code></li>
<li><code>firebasedynamiclinks. domains. get</code></li>
<li><code>firebasedynamiclinks. domains. list</code></li>
<li><code>firebasedynamiclinks. domains. update</code></li>
<li><code>firebasedynamiclinks. links. create</code></li>
<li><code>firebasedynamiclinks.links.get</code></li>
<li><code>firebasedynamiclinks. links. list</code></li>
<li><code>firebasedynamiclinks. links. update</code></li>
<li><code>firebasedynamiclinks.stats.get</code></li>
</ul>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseinappmessaging.*</code></p>
<ul>
<li><code>firebaseinappmessaging. campaigns. create</code></li>
<li><code>firebaseinappmessaging. campaigns. delete</code></li>
<li><code>firebaseinappmessaging. campaigns. get</code></li>
<li><code>firebaseinappmessaging. campaigns. list</code></li>
<li><code>firebaseinappmessaging. campaigns. update</code></li>
</ul>
<p><code>firebasemessagingcampaigns.*</code></p>
<ul>
<li><code>firebasemessagingcampaigns. campaigns. create</code></li>
<li><code>firebasemessagingcampaigns. campaigns. delete</code></li>
<li><code>firebasemessagingcampaigns. campaigns. get</code></li>
<li><code>firebasemessagingcampaigns. campaigns. list</code></li>
<li><code>firebasemessagingcampaigns. campaigns. start</code></li>
<li><code>firebasemessagingcampaigns. campaigns. stop</code></li>
<li><code>firebasemessagingcampaigns. campaigns. update</code></li>
</ul>
<p><code>firebasenotifications.*</code></p>
<ul>
<li><code>firebasenotifications. messages. create</code></li>
<li><code>firebasenotifications. messages. delete</code></li>
<li><code>firebasenotifications. messages. get</code></li>
<li><code>firebasenotifications. messages. list</code></li>
<li><code>firebasenotifications. messages. update</code></li>
</ul>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Grow Viewer
<p>( <code>roles/ firebase.growthViewer</code> )</p>
<p>Read access to Firebase Grow products and Analytics.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>cloudconfig.configs.get</code></p>
<p><code>cloudmessaging. topicSubscriptions. get</code></p>
<p><code>cloudmessaging. topicSubscriptions. list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseabt. experimentresults. get</code></p>
<p><code>firebaseabt.experiments.get</code></p>
<p><code>firebaseabt.experiments.list</code></p>
<p><code>firebaseabt. projectmetadata. get</code></p>
<p><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></p>
<p><code>firebasedynamiclinks. destinations. list</code></p>
<p><code>firebasedynamiclinks. domains. get</code></p>
<p><code>firebasedynamiclinks. domains. list</code></p>
<p><code>firebasedynamiclinks.links.get</code></p>
<p><code>firebasedynamiclinks. links. list</code></p>
<p><code>firebasedynamiclinks.stats.get</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseinappmessaging. campaigns. get</code></p>
<p><code>firebaseinappmessaging. campaigns. list</code></p>
<p><code>firebasemessagingcampaigns. campaigns. get</code></p>
<p><code>firebasemessagingcampaigns. campaigns. list</code></p>
<p><code>firebasenotifications. messages. get</code></p>
<p><code>firebasenotifications. messages. list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Firebase Quality Admin
<p>( <code>roles/ firebase.qualityAdmin</code> )</p>
<p>Full access to Firebase Quality products and Analytics.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseanalytics.*</code></p>
<ul>
<li><code>firebaseanalytics. resources. googleAnalyticsEdit</code></li>
<li><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></li>
</ul>
<p><code>firebaseappdistro.*</code></p>
<ul>
<li><code>firebaseappdistro.groups.list</code></li>
<li><code>firebaseappdistro. groups. update</code></li>
<li><code>firebaseappdistro. releases. list</code></li>
<li><code>firebaseappdistro. releases. update</code></li>
<li><code>firebaseappdistro.testers.list</code></li>
<li><code>firebaseappdistro. testers. update</code></li>
</ul>
<p><code>firebasecrash.*</code></p>
<ul>
<li><code>firebasecrash.issues.update</code></li>
<li><code>firebasecrash.reports.get</code></li>
</ul>
<p><code>firebasecrashlytics.*</code></p>
<ul>
<li><code>firebasecrashlytics.config.get</code></li>
<li><code>firebasecrashlytics. config. update</code></li>
<li><code>firebasecrashlytics.data.get</code></li>
<li><code>firebasecrashlytics.issues.get</code></li>
<li><code>firebasecrashlytics. issues. list</code></li>
<li><code>firebasecrashlytics. issues. update</code></li>
<li><code>firebasecrashlytics. sessions. get</code></li>
</ul>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseperformance.*</code></p>
<ul>
<li><code>firebaseperformance. config. update</code></li>
<li><code>firebaseperformance.data.get</code></li>
</ul>
<p><code>logging.logEntries.download</code></p>
<p><code>logging.views.access</code></p>
<p><code>logging.views.listLogs</code></p>
<p><code>logging.views.listResourceKeys</code></p>
<p><code>logging. views. listResourceValues</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Quality Viewer
<p>( <code>roles/ firebase.qualityViewer</code> )</p>
<p>Read access to Firebase Quality products and Analytics.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>firebase.billingPlans.get</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.get</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseanalytics. resources. googleAnalyticsReadAndAnalyze</code></p>
<p><code>firebaseappdistro.groups.list</code></p>
<p><code>firebaseappdistro. releases. list</code></p>
<p><code>firebaseappdistro.testers.list</code></p>
<p><code>firebasecrash.reports.get</code></p>
<p><code>firebasecrashlytics.config.get</code></p>
<p><code>firebasecrashlytics.data.get</code></p>
<p><code>firebasecrashlytics.issues.get</code></p>
<p><code>firebasecrashlytics. issues. list</code></p>
<p><code>firebasecrashlytics. sessions. get</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseperformance.data.get</code></p>
<p><code>logging.logEntries.download</code></p>
<p><code>logging.views.access</code></p>
<p><code>logging.views.listLogs</code></p>
<p><code>logging.views.listResourceKeys</code></p>
<p><code>logging. views. listResourceValues</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
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
<td>Firebase App Distribution Admin SDK Service Agent
<p>( <code>roles/ firebase.appDistributionSdkServiceAgent</code> )</p>
<p>Read and write access to Firebase App Distribution with the Admin SDK</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>firebaseappdistro.*</code></p>
<ul>
<li><code>firebaseappdistro.groups.list</code></li>
<li><code>firebaseappdistro. groups. update</code></li>
<li><code>firebaseappdistro. releases. list</code></li>
<li><code>firebaseappdistro. releases. update</code></li>
<li><code>firebaseappdistro.testers.list</code></li>
<li><code>firebaseappdistro. testers. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Firebase Service Management Service Agent
<p>( <code>roles/ firebase.managementServiceAgent</code> )</p>
<p>Access to create new service agents for Firebase projects; assign roles to service agents; provision GCP resources as required by Firebase services.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>apikeys.keys.create</code></p>
<p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.getKeyString</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>apikeys.keys.update</code></p>
<p><code>appengine.applications.create</code></p>
<p><code>appengine.applications.get</code></p>
<p><code>appengine.applications.update</code></p>
<p><code>appengine.operations.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery.datasets.setIamPolicy</code></p>
<p><code>bigquery.datasets.update</code></p>
<p><code>bigquery.transfers.*</code></p>
<ul>
<li><code>bigquery.transfers.get</code></li>
<li><code>bigquery.transfers.update</code></li>
</ul>
<p><code>clientauthconfig.brands.create</code></p>
<p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig.brands.update</code></p>
<p><code>clientauthconfig. clients. create</code></p>
<p><code>clientauthconfig. clients. delete</code></p>
<p><code>clientauthconfig.clients.get</code></p>
<p><code>clientauthconfig. clients. getWithSecret</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>clientauthconfig. clients. update</code></p>
<p><code>datastore.databases.create</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.databases.update</code></p>
<p><code>datastore.locations.*</code></p>
<ul>
<li><code>datastore.locations.get</code></li>
<li><code>datastore.locations.list</code></li>
</ul>
<p><code>datastore.operations.get</code></p>
<p><code>datastore.operations.list</code></p>
<p><code>firebase.clients.create</code></p>
<p><code>firebase.clients.delete</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.undelete</code></p>
<p><code>firebase.clients.update</code></p>
<p><code>firebase.projects.*</code></p>
<ul>
<li><code>firebase.projects.delete</code></li>
<li><code>firebase.projects.get</code></li>
<li><code>firebase.projects.update</code></li>
</ul>
<p><code>firebaseabt.experiments.delete</code></p>
<p><code>firebaseappcheck. recaptchaEnterpriseConfig.*</code></p>
<ul>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. update</code></li>
</ul>
<p><code>firebaseappcheck. recaptchaV3Config. get</code></p>
<p><code>firebaseappcheck.services.*</code></p>
<ul>
<li><code>firebaseappcheck.services.get</code></li>
<li><code>firebaseappcheck. services. update</code></li>
</ul>
<p><code>firebaseapphosting. domains. create</code></p>
<p><code>firebaseapphosting.domains.get</code></p>
<p><code>firebaseapphosting. domains. list</code></p>
<p><code>firebaseapphosting. domains. update</code></p>
<p><code>firebaseauth.configs.create</code></p>
<p><code>firebaseauth.configs.get</code></p>
<p><code>firebaseauth.configs.update</code></p>
<p><code>firebasedataconnect. locations.*</code></p>
<ul>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
</ul>
<p><code>firebasedataconnect. operations. get</code></p>
<p><code>firebasedataconnect. operations. list</code></p>
<p><code>firebasedataconnect. services. create</code></p>
<p><code>firebasehosting.sites.create</code></p>
<p><code>firebasehosting.sites.get</code></p>
<p><code>firebasehosting.sites.list</code></p>
<p><code>firebasehosting.sites.update</code></p>
<p><code>firebaserules.releases.create</code></p>
<p><code>firebaserules.releases.delete</code></p>
<p><code>firebaserules.releases.get</code></p>
<p><code>firebaserules.releases.list</code></p>
<p><code>firebaserules.releases.update</code></p>
<p><code>firebaserules.rulesets.create</code></p>
<p><code>firebaserules.rulesets.get</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>firebasestorage. defaultBucket. get</code></p>
<p><code>firebasevertexai.configs.*</code></p>
<ul>
<li><code>firebasevertexai.configs.get</code></li>
<li><code>firebasevertexai. configs. update</code></li>
</ul>
<p><code>iam.roles.get</code></p>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>recaptchaenterprise. keys. create</code></p>
<p><code>recaptchaenterprise.keys.get</code></p>
<p><code>recaptchaenterprise.keys.list</code></p>
<p><code>recaptchaenterprise. keys. update</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
<p><code>resourcemanager. projects. update</code></p>
<p><code>servicemanagement. services. bind</code></p>
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
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.bucketOperations.get</code></p>
<p><code>storage.bucketOperations.list</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.setIamPolicy</code></p>
<p><code>storage.buckets.update</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Admin SDK Administrator Service Agent
<p>( <code>roles/ firebase.sdkAdminServiceAgent</code> )</p>
<p>Read and write access to Firebase products available in the Admin SDK</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>cloudconfig.*</code></p>
<ul>
<li><code>cloudconfig.configs.get</code></li>
<li><code>cloudconfig.configs.update</code></li>
</ul>
<p><code>cloudmessaging.messages.create</code></p>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries. create</code></p>
<p><code>databasesconsole. studioQueries. delete</code></p>
<p><code>databasesconsole. studioQueries. search</code></p>
<p><code>databasesconsole. studioQueries. update</code></p>
<p><code>datastore.backupSchedules.get</code></p>
<p><code>datastore.backupSchedules.list</code></p>
<p><code>datastore.backups.get</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore. databases. listEffectiveTags</code></p>
<p><code>datastore. databases. listTagBindings</code></p>
<p><code>datastore.entities.*</code></p>
<ul>
<li><code>datastore.entities.allocateIds</code></li>
<li><code>datastore.entities.create</code></li>
<li><code>datastore.entities.delete</code></li>
<li><code>datastore.entities.get</code></li>
<li><code>datastore.entities.list</code></li>
<li><code>datastore.entities.update</code></li>
</ul>
<p><code>datastore.insights.get</code></p>
<p><code>datastore.keyVisualizerScans.*</code></p>
<ul>
<li><code>datastore. keyVisualizerScans. get</code></li>
<li><code>datastore. keyVisualizerScans. list</code></li>
</ul>
<p><code>datastore.namespaces.*</code></p>
<ul>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
</ul>
<p><code>datastore.operations.get</code></p>
<p><code>datastore.operations.list</code></p>
<p><code>datastore.schemas.get</code></p>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.*</code></p>
<ul>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
</ul>
<p><code>datastore.userCreds.get</code></p>
<p><code>datastore.userCreds.list</code></p>
<p><code>firebase.clients.*</code></p>
<ul>
<li><code>firebase.clients.create</code></li>
<li><code>firebase.clients.delete</code></li>
<li><code>firebase.clients.get</code></li>
<li><code>firebase.clients.list</code></li>
<li><code>firebase.clients.undelete</code></li>
<li><code>firebase.clients.update</code></li>
</ul>
<p><code>firebase.projects.get</code></p>
<p><code>firebase.projects.update</code></p>
<p><code>firebaseappcheck.*</code></p>
<ul>
<li><code>firebaseappcheck. appAttestConfig. get</code></li>
<li><code>firebaseappcheck. appAttestConfig. update</code></li>
<li><code>firebaseappcheck. appCheckTokens. verify</code></li>
<li><code>firebaseappcheck. automations. create</code></li>
<li><code>firebaseappcheck. automations. delete</code></li>
<li><code>firebaseappcheck. automations. get</code></li>
<li><code>firebaseappcheck. automations. list</code></li>
<li><code>firebaseappcheck. automations. resume</code></li>
<li><code>firebaseappcheck. automations. suspend</code></li>
<li><code>firebaseappcheck. automations. update</code></li>
<li><code>firebaseappcheck. debugTokens. get</code></li>
<li><code>firebaseappcheck. debugTokens. update</code></li>
<li><code>firebaseappcheck. deviceCheckConfig. get</code></li>
<li><code>firebaseappcheck. deviceCheckConfig. update</code></li>
<li><code>firebaseappcheck. playIntegrityConfig. get</code></li>
<li><code>firebaseappcheck. playIntegrityConfig. update</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. get</code></li>
<li><code>firebaseappcheck. recaptchaEnterpriseConfig. update</code></li>
<li><code>firebaseappcheck. recaptchaV3Config. get</code></li>
<li><code>firebaseappcheck. recaptchaV3Config. update</code></li>
<li><code>firebaseappcheck. resourcePolicies. get</code></li>
<li><code>firebaseappcheck. resourcePolicies. update</code></li>
<li><code>firebaseappcheck. safetyNetConfig. get</code></li>
<li><code>firebaseappcheck. safetyNetConfig. update</code></li>
<li><code>firebaseappcheck.services.get</code></li>
<li><code>firebaseappcheck. services. update</code></li>
<li><code>firebaseappcheck.tokens.mint</code></li>
</ul>
<p><code>firebaseauth.configs.create</code></p>
<p><code>firebaseauth.configs.get</code></p>
<p><code>firebaseauth.configs.getSecret</code></p>
<p><code>firebaseauth.configs.update</code></p>
<p><code>firebaseauth.users.*</code></p>
<ul>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>firebasedatabase.*</code></p>
<ul>
<li><code>firebasedatabase. instances. create</code></li>
<li><code>firebasedatabase. instances. delete</code></li>
<li><code>firebasedatabase. instances. disable</code></li>
<li><code>firebasedatabase.instances.get</code></li>
<li><code>firebasedatabase. instances. list</code></li>
<li><code>firebasedatabase. instances. reenable</code></li>
<li><code>firebasedatabase. instances. undelete</code></li>
<li><code>firebasedatabase. instances. update</code></li>
</ul>
<p><code>firebasedataconnect. connectorRevisions.*</code></p>
<ul>
<li><code>firebasedataconnect. connectorRevisions. delete</code></li>
<li><code>firebasedataconnect. connectorRevisions. get</code></li>
<li><code>firebasedataconnect. connectorRevisions. list</code></li>
</ul>
<p><code>firebasedataconnect. connectors.*</code></p>
<ul>
<li><code>firebasedataconnect. connectors. create</code></li>
<li><code>firebasedataconnect. connectors. delete</code></li>
<li><code>firebasedataconnect. connectors. get</code></li>
<li><code>firebasedataconnect. connectors. impersonateMutation</code></li>
<li><code>firebasedataconnect. connectors. impersonateQuery</code></li>
<li><code>firebasedataconnect. connectors. list</code></li>
<li><code>firebasedataconnect. connectors. update</code></li>
</ul>
<p><code>firebasedataconnect. locations.*</code></p>
<ul>
<li><code>firebasedataconnect. locations. get</code></li>
<li><code>firebasedataconnect. locations. list</code></li>
</ul>
<p><code>firebasedataconnect. operations.*</code></p>
<ul>
<li><code>firebasedataconnect. operations. cancel</code></li>
<li><code>firebasedataconnect. operations. delete</code></li>
<li><code>firebasedataconnect. operations. get</code></li>
<li><code>firebasedataconnect. operations. list</code></li>
</ul>
<p><code>firebasedataconnect. schemaRevisions.*</code></p>
<ul>
<li><code>firebasedataconnect. schemaRevisions. delete</code></li>
<li><code>firebasedataconnect. schemaRevisions. get</code></li>
<li><code>firebasedataconnect. schemaRevisions. list</code></li>
</ul>
<p><code>firebasedataconnect. schemas. create</code></p>
<p><code>firebasedataconnect. schemas. delete</code></p>
<p><code>firebasedataconnect. schemas. get</code></p>
<p><code>firebasedataconnect. schemas. list</code></p>
<p><code>firebasedataconnect. schemas. update</code></p>
<p><code>firebasedataconnect. services. create</code></p>
<p><code>firebasedataconnect. services. delete</code></p>
<p><code>firebasedataconnect. services. executeGraphql</code></p>
<p><code>firebasedataconnect. services. executeGraphqlRead</code></p>
<p><code>firebasedataconnect. services. get</code></p>
<p><code>firebasedataconnect. services. introspectGraphql</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebasedataconnect. services. update</code></p>
<p><code>firebasehosting.*</code></p>
<ul>
<li><code>firebasehosting.sites.create</code></li>
<li><code>firebasehosting.sites.delete</code></li>
<li><code>firebasehosting.sites.get</code></li>
<li><code>firebasehosting.sites.list</code></li>
<li><code>firebasehosting.sites.update</code></li>
</ul>
<p><code>firebaseml.*</code></p>
<ul>
<li><code>firebaseml.models.create</code></li>
<li><code>firebaseml.models.delete</code></li>
<li><code>firebaseml.models.get</code></li>
<li><code>firebaseml.models.list</code></li>
<li><code>firebaseml.models.update</code></li>
<li><code>firebaseml. modelversions. create</code></li>
<li><code>firebaseml.modelversions.get</code></li>
<li><code>firebaseml.modelversions.list</code></li>
<li><code>firebaseml. modelversions. update</code></li>
</ul>
<p><code>firebasenotifications.*</code></p>
<ul>
<li><code>firebasenotifications. messages. create</code></li>
<li><code>firebasenotifications. messages. delete</code></li>
<li><code>firebasenotifications. messages. get</code></li>
<li><code>firebasenotifications. messages. list</code></li>
<li><code>firebasenotifications. messages. update</code></li>
</ul>
<p><code>firebaserules.releases.get</code></p>
<p><code>firebaserules.releases.list</code></p>
<p><code>firebaserules.releases.update</code></p>
<p><code>firebaserules.rulesets.create</code></p>
<p><code>firebaserules.rulesets.delete</code></p>
<p><code>firebaserules.rulesets.get</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>identitytoolkit.*</code></p>
<ul>
<li><code>identitytoolkit.tenants.create</code></li>
<li><code>identitytoolkit.tenants.delete</code></li>
<li><code>identitytoolkit.tenants.get</code></li>
<li><code>identitytoolkit. tenants. getIamPolicy</code></li>
<li><code>identitytoolkit.tenants.list</code></li>
<li><code>identitytoolkit. tenants. setIamPolicy</code></li>
<li><code>identitytoolkit.tenants.update</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager. projects. update</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.managedFolders.update</code></p>
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
</ul></td>
</tr>
<tr class="even">
<td>Firebase SDK Provisioning Service Agent
<p>( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</p>
<p>Access to provision apps with the Admin SDK.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>apikeys.keys.list</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>cloudmessaging.messages.create</code></p>
<p><code>firebase.clients.create</code></p>
<p><code>servicemanagement. services. bind</code></p>
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
<p><code>serviceusage.values.test</code></p></td>
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
<td><code>firebase.billingPlans.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>firebase.billingPlans.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>firebase.clients.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code>roles/ oauthconfig.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>firebase.clients.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>firebase.clients.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code>roles/ cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code>roles/ cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code>roles/ firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code>roles/ firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code>roles/ firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code>roles/ firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code>roles/ firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code>roles/ firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code>roles/ firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code>roles/ firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code>roles/ firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code>roles/ firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code>roles/ firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code>roles/ firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code>roles/ firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code>roles/ firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code>roles/ firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code>roles/ firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code>roles/ firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code>roles/ firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code>roles/ firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code>roles/ firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code>roles/ firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code>roles/ firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code>roles/ firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code>roles/ firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code>roles/ firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code>roles/ firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code>roles/ firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code>roles/ oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code>roles/ oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrash.symbolMappingsAdmin">Firebase Crash Symbol Uploader</a> ( <code>roles/ firebasecrash.symbolMappingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code>roles/ firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code>roles/ firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code>roles/ firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>firebase.clients.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code>roles/ cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code>roles/ cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code>roles/ firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code>roles/ firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code>roles/ firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code>roles/ firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code>roles/ firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code>roles/ firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code>roles/ firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code>roles/ firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code>roles/ firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code>roles/ firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code>roles/ firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code>roles/ firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code>roles/ firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code>roles/ firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code>roles/ firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code>roles/ firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code>roles/ firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code>roles/ firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code>roles/ firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code>roles/ firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code>roles/ firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code>roles/ firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code>roles/ firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code>roles/ firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code>roles/ firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code>roles/ firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code>roles/ firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code>roles/ oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code>roles/ oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrash.symbolMappingsAdmin">Firebase Crash Symbol Uploader</a> ( <code>roles/ firebasecrash.symbolMappingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code>roles/ firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code>roles/ firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code>roles/ firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>firebase.clients.undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>firebase.clients.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code>roles/ oauthconfig.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>firebase.links.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>firebase.links.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>firebase.links.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>firebase.links.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>firebase.playLinks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>firebase.playLinks.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>firebase.playLinks.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>firebase.projects.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>firebase.projects.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code>roles/ actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code>roles/ actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code>roles/ cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code>roles/ cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code>roles/ firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code>roles/ firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code>roles/ firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code>roles/ firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code>roles/ firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code>roles/ firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code>roles/ firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code>roles/ firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code>roles/ firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code>roles/ firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code>roles/ firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code>roles/ firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code>roles/ firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code>roles/ firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code>roles/ firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code>roles/ firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code>roles/ firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code>roles/ firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code>roles/ firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code>roles/ firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code>roles/ firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code>roles/ firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code>roles/ firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code>roles/ firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code>roles/ firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code>roles/ firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code>roles/ firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code>roles/ firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code>roles/ firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code>roles/ firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>firebase.projects.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code>roles/ actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
