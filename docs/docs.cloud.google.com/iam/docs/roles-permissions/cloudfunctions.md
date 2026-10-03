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
<td>Cloud Functions Admin
<p>( <code>roles/ cloudfunctions.admin</code> )</p>
<p>Full access to functions, operations and locations.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
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
<p><code>remotebuildexecution.blobs.get</code></p>
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
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Cloud Functions Editor
<p>( <code>roles/ cloudfunctions.editor</code> )</p>
<p>Editor role for Cloud Functions</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
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
<p><code>cloudfunctions.functions.call</code></p>
<p><code>cloudfunctions. functions. create</code></p>
<p><code>cloudfunctions. functions. delete</code></p>
<p><code>cloudfunctions. functions. generationUpgrade</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions. functions. invoke</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions. functions. sourceCodeGet</code></p>
<p><code>cloudfunctions. functions. sourceCodeSet</code></p>
<p><code>cloudfunctions. functions. update</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.*</code></p>
<ul>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>eventarc. channelConnections. create</code></p>
<p><code>eventarc. channelConnections. delete</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channelConnections. publish</code></p>
<p><code>eventarc.channels.attach</code></p>
<p><code>eventarc.channels.create</code></p>
<p><code>eventarc.channels.delete</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc.channels.publish</code></p>
<p><code>eventarc.channels.undelete</code></p>
<p><code>eventarc.channels.update</code></p>
<p><code>eventarc.enrollments.create</code></p>
<p><code>eventarc.enrollments.delete</code></p>
<p><code>eventarc.enrollments.get</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.enrollments.update</code></p>
<p><code>eventarc. googleApiSources. create</code></p>
<p><code>eventarc. googleApiSources. delete</code></p>
<p><code>eventarc.googleApiSources.get</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleApiSources. update</code></p>
<p><code>eventarc. googleChannelConfigs.*</code></p>
<ul>
<li><code>eventarc. googleChannelConfigs. get</code></li>
<li><code>eventarc. googleChannelConfigs. update</code></li>
</ul>
<p><code>eventarc.kafkaSources.create</code></p>
<p><code>eventarc.kafkaSources.delete</code></p>
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
<p><code>eventarc.operations.*</code></p>
<ul>
<li><code>eventarc.operations.cancel</code></li>
<li><code>eventarc.operations.delete</code></li>
<li><code>eventarc.operations.get</code></li>
<li><code>eventarc.operations.list</code></li>
</ul>
<p><code>eventarc.pipelines.create</code></p>
<p><code>eventarc.pipelines.delete</code></p>
<p><code>eventarc.pipelines.get</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.pipelines.update</code></p>
<p><code>eventarc.providers.*</code></p>
<ul>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
</ul>
<p><code>eventarc.triggers.create</code></p>
<p><code>eventarc.triggers.delete</code></p>
<p><code>eventarc.triggers.get</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>eventarc.triggers.undelete</code></p>
<p><code>eventarc.triggers.update</code></p>
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
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.configurations.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
</ul>
<p><code>run.executions.*</code></p>
<ul>
<li><code>run.executions.cancel</code></li>
<li><code>run.executions.delete</code></li>
<li><code>run.executions.get</code></li>
<li><code>run.executions.list</code></li>
</ul>
<p><code>run.instances.create</code></p>
<p><code>run.instances.delete</code></p>
<p><code>run.instances.get</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.invoke</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.instances.sshRead</code></p>
<p><code>run.instances.sshRoot</code></p>
<p><code>run.instances.start</code></p>
<p><code>run.instances.stop</code></p>
<p><code>run.instances.update</code></p>
<p><code>run.jobs.create</code></p>
<p><code>run.jobs.delete</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.jobs.run</code></p>
<p><code>run.jobs.runWithOverrides</code></p>
<p><code>run.jobs.sshRead</code></p>
<p><code>run.jobs.sshRoot</code></p>
<p><code>run.jobs.update</code></p>
<p><code>run.locations.*</code></p>
<ul>
<li><code>run.locations.list</code></li>
<li><code>run.locations.uploadSource</code></li>
</ul>
<p><code>run.operations.*</code></p>
<ul>
<li><code>run.operations.delete</code></li>
<li><code>run.operations.get</code></li>
<li><code>run.operations.list</code></li>
</ul>
<p><code>run.prompts.get</code></p>
<p><code>run.revisions.*</code></p>
<ul>
<li><code>run.revisions.delete</code></li>
<li><code>run.revisions.get</code></li>
<li><code>run.revisions.list</code></li>
</ul>
<p><code>run.routes.*</code></p>
<ul>
<li><code>run.routes.get</code></li>
<li><code>run.routes.invoke</code></li>
<li><code>run.routes.list</code></li>
</ul>
<p><code>run.services.create</code></p>
<p><code>run.services.delete</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>run.services.sshRead</code></p>
<p><code>run.services.sshRoot</code></p>
<p><code>run.services.update</code></p>
<p><code>run.tasks.*</code></p>
<ul>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
</ul>
<p><code>run.workerpools.create</code></p>
<p><code>run.workerpools.delete</code></p>
<p><code>run.workerpools.get</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>run.workerpools.sshRead</code></p>
<p><code>run.workerpools.sshRoot</code></p>
<p><code>run.workerpools.update</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Functions Invoker
<p>( <code>roles/ cloudfunctions.invoker</code> )</p>
<p>Ability to invoke 1st gen HTTP functions with restricted access. 2nd gen functions need the Cloud Run Invoker role instead.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
<td><p><code>cloudfunctions. functions. invoke</code></p></td>
</tr>
<tr class="even">
<td>Cloud Functions Viewer
<p>( <code>roles/ cloudfunctions.viewer</code> )</p>
<p>Read-only access to functions and locations.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
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
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Functions Developer
<p>( <code>roles/ cloudfunctions.developer</code> )</p>
<p>Read and write access to all functions-related resources.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p></td>
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
<p><code>cloudfunctions.functions.call</code></p>
<p><code>cloudfunctions. functions. create</code></p>
<p><code>cloudfunctions. functions. delete</code></p>
<p><code>cloudfunctions. functions. generationUpgrade</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. invoke</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions. functions. sourceCodeGet</code></p>
<p><code>cloudfunctions. functions. sourceCodeSet</code></p>
<p><code>cloudfunctions. functions. update</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.*</code></p>
<ul>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>eventarc. channelConnections. create</code></p>
<p><code>eventarc. channelConnections. createTagBinding</code></p>
<p><code>eventarc. channelConnections. delete</code></p>
<p><code>eventarc. channelConnections. deleteTagBinding</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channelConnections. publish</code></p>
<p><code>eventarc.channels.attach</code></p>
<p><code>eventarc.channels.create</code></p>
<p><code>eventarc. channels. createTagBinding</code></p>
<p><code>eventarc.channels.delete</code></p>
<p><code>eventarc. channels. deleteTagBinding</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc.channels.publish</code></p>
<p><code>eventarc.channels.undelete</code></p>
<p><code>eventarc.channels.update</code></p>
<p><code>eventarc.enrollments.create</code></p>
<p><code>eventarc.enrollments.delete</code></p>
<p><code>eventarc.enrollments.get</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.enrollments.update</code></p>
<p><code>eventarc. googleApiSources. create</code></p>
<p><code>eventarc. googleApiSources. delete</code></p>
<p><code>eventarc.googleApiSources.get</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleApiSources. update</code></p>
<p><code>eventarc. googleChannelConfigs.*</code></p>
<ul>
<li><code>eventarc. googleChannelConfigs. get</code></li>
<li><code>eventarc. googleChannelConfigs. update</code></li>
</ul>
<p><code>eventarc.kafkaSources.create</code></p>
<p><code>eventarc.kafkaSources.delete</code></p>
<p><code>eventarc.kafkaSources.get</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc.locations.*</code></p>
<ul>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
</ul>
<p><code>eventarc.operations.*</code></p>
<ul>
<li><code>eventarc.operations.cancel</code></li>
<li><code>eventarc.operations.delete</code></li>
<li><code>eventarc.operations.get</code></li>
<li><code>eventarc.operations.list</code></li>
</ul>
<p><code>eventarc.pipelines.create</code></p>
<p><code>eventarc.pipelines.delete</code></p>
<p><code>eventarc.pipelines.get</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.pipelines.update</code></p>
<p><code>eventarc.providers.*</code></p>
<ul>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
</ul>
<p><code>eventarc.triggers.create</code></p>
<p><code>eventarc. triggers. createTagBinding</code></p>
<p><code>eventarc.triggers.delete</code></p>
<p><code>eventarc. triggers. deleteTagBinding</code></p>
<p><code>eventarc.triggers.get</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>eventarc.triggers.undelete</code></p>
<p><code>eventarc.triggers.update</code></p>
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
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.configurations.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
</ul>
<p><code>run.executions.*</code></p>
<ul>
<li><code>run.executions.cancel</code></li>
<li><code>run.executions.delete</code></li>
<li><code>run.executions.get</code></li>
<li><code>run.executions.list</code></li>
</ul>
<p><code>run.instances.create</code></p>
<p><code>run.instances.delete</code></p>
<p><code>run.instances.get</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.invoke</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.instances.sshRead</code></p>
<p><code>run.instances.sshRoot</code></p>
<p><code>run.instances.start</code></p>
<p><code>run.instances.stop</code></p>
<p><code>run.instances.update</code></p>
<p><code>run.jobs.create</code></p>
<p><code>run.jobs.delete</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.jobs.run</code></p>
<p><code>run.jobs.runWithOverrides</code></p>
<p><code>run.jobs.sshRead</code></p>
<p><code>run.jobs.sshRoot</code></p>
<p><code>run.jobs.update</code></p>
<p><code>run.locations.*</code></p>
<ul>
<li><code>run.locations.list</code></li>
<li><code>run.locations.uploadSource</code></li>
</ul>
<p><code>run.operations.*</code></p>
<ul>
<li><code>run.operations.delete</code></li>
<li><code>run.operations.get</code></li>
<li><code>run.operations.list</code></li>
</ul>
<p><code>run.prompts.get</code></p>
<p><code>run.revisions.*</code></p>
<ul>
<li><code>run.revisions.delete</code></li>
<li><code>run.revisions.get</code></li>
<li><code>run.revisions.list</code></li>
</ul>
<p><code>run.routes.*</code></p>
<ul>
<li><code>run.routes.get</code></li>
<li><code>run.routes.invoke</code></li>
<li><code>run.routes.list</code></li>
</ul>
<p><code>run.services.create</code></p>
<p><code>run.services.delete</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>run.services.sshRead</code></p>
<p><code>run.services.sshRoot</code></p>
<p><code>run.services.update</code></p>
<p><code>run.tasks.*</code></p>
<ul>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
</ul>
<p><code>run.workerpools.create</code></p>
<p><code>run.workerpools.delete</code></p>
<p><code>run.workerpools.get</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>run.workerpools.sshRead</code></p>
<p><code>run.workerpools.sshRoot</code></p>
<p><code>run.workerpools.update</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
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
<td>(Deprecated) Cloud Functions Service Agent
<p>( <code>roles/ cloudfunctions.serviceAgent</code> )</p>
<p>Gives Cloud Functions service account access to managed resources.</p>
<p>This role applies to functions created using the Cloud Functions API. For functions created using Cloud Run, refer to the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run">Cloud Run roles and permissions</a> page.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. aptartifacts. create</code></p>
<p><code>artifactregistry.attachments.*</code></p>
<ul>
<li><code>artifactregistry. attachments. create</code></li>
<li><code>artifactregistry. attachments. delete</code></li>
<li><code>artifactregistry. attachments. get</code></li>
<li><code>artifactregistry. attachments. list</code></li>
</ul>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry.files.*</code></p>
<ul>
<li><code>artifactregistry.files.delete</code></li>
<li><code>artifactregistry. files. download</code></li>
<li><code>artifactregistry.files.get</code></li>
<li><code>artifactregistry.files.list</code></li>
<li><code>artifactregistry.files.update</code></li>
<li><code>artifactregistry.files.upload</code></li>
</ul>
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
<p><code>artifactregistry.packages.*</code></p>
<ul>
<li><code>artifactregistry. packages. delete</code></li>
<li><code>artifactregistry.packages.get</code></li>
<li><code>artifactregistry.packages.list</code></li>
<li><code>artifactregistry. packages. update</code></li>
</ul>
<p><code>artifactregistry. projectconfigs.*</code></p>
<ul>
<li><code>artifactregistry. projectconfigs. get</code></li>
<li><code>artifactregistry. projectconfigs. update</code></li>
</ul>
<p><code>artifactregistry. projectsettings.*</code></p>
<ul>
<li><code>artifactregistry. projectsettings. get</code></li>
<li><code>artifactregistry. projectsettings. update</code></li>
</ul>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. createTagBinding</code></p>
<p><code>artifactregistry. repositories. delete</code></p>
<p><code>artifactregistry. repositories. deleteArtifacts</code></p>
<p><code>artifactregistry. repositories. deleteTagBinding</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. exportArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. getIamPolicy</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry. repositories. setIamPolicy</code></p>
<p><code>artifactregistry. repositories. update</code></p>
<p><code>artifactregistry. repositories. uploadArtifacts</code></p>
<p><code>artifactregistry.rules.*</code></p>
<ul>
<li><code>artifactregistry.rules.create</code></li>
<li><code>artifactregistry.rules.delete</code></li>
<li><code>artifactregistry.rules.get</code></li>
<li><code>artifactregistry.rules.list</code></li>
<li><code>artifactregistry.rules.update</code></li>
</ul>
<p><code>artifactregistry.tags.*</code></p>
<ul>
<li><code>artifactregistry.tags.create</code></li>
<li><code>artifactregistry.tags.delete</code></li>
<li><code>artifactregistry.tags.get</code></li>
<li><code>artifactregistry.tags.list</code></li>
<li><code>artifactregistry.tags.update</code></li>
</ul>
<p><code>artifactregistry.versions.*</code></p>
<ul>
<li><code>artifactregistry. versions. delete</code></li>
<li><code>artifactregistry.versions.get</code></li>
<li><code>artifactregistry.versions.list</code></li>
<li><code>artifactregistry. versions. update</code></li>
</ul>
<p><code>artifactregistry. yumartifacts. create</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.builds.update</code></p>
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
<p><code>cloudbuild.workerpools.use</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. invoke</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions.operations.*</code></p>
<ul>
<li><code>cloudfunctions.operations.get</code></li>
<li><code>cloudfunctions.operations.list</code></li>
</ul>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.networks.access</code></p>
<p><code>eventarc. channelConnections. create</code></p>
<p><code>eventarc. channelConnections. delete</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channelConnections. publish</code></p>
<p><code>eventarc.channels.attach</code></p>
<p><code>eventarc.channels.create</code></p>
<p><code>eventarc.channels.delete</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc.channels.publish</code></p>
<p><code>eventarc.channels.undelete</code></p>
<p><code>eventarc.channels.update</code></p>
<p><code>eventarc.enrollments.create</code></p>
<p><code>eventarc.enrollments.delete</code></p>
<p><code>eventarc.enrollments.get</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.enrollments.update</code></p>
<p><code>eventarc. googleApiSources. create</code></p>
<p><code>eventarc. googleApiSources. delete</code></p>
<p><code>eventarc.googleApiSources.get</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleApiSources. update</code></p>
<p><code>eventarc. googleChannelConfigs.*</code></p>
<ul>
<li><code>eventarc. googleChannelConfigs. get</code></li>
<li><code>eventarc. googleChannelConfigs. update</code></li>
</ul>
<p><code>eventarc.kafkaSources.create</code></p>
<p><code>eventarc.kafkaSources.delete</code></p>
<p><code>eventarc.kafkaSources.get</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc.locations.*</code></p>
<ul>
<li><code>eventarc.locations.get</code></li>
<li><code>eventarc.locations.list</code></li>
</ul>
<p><code>eventarc.operations.*</code></p>
<ul>
<li><code>eventarc.operations.cancel</code></li>
<li><code>eventarc.operations.delete</code></li>
<li><code>eventarc.operations.get</code></li>
<li><code>eventarc.operations.list</code></li>
</ul>
<p><code>eventarc.pipelines.create</code></p>
<p><code>eventarc.pipelines.delete</code></p>
<p><code>eventarc.pipelines.get</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.pipelines.update</code></p>
<p><code>eventarc.providers.*</code></p>
<ul>
<li><code>eventarc.providers.get</code></li>
<li><code>eventarc.providers.list</code></li>
</ul>
<p><code>eventarc.triggers.create</code></p>
<p><code>eventarc.triggers.delete</code></p>
<p><code>eventarc.triggers.get</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>eventarc.triggers.undelete</code></p>
<p><code>eventarc.triggers.update</code></p>
<p><code>firebasedatabase.instances.get</code></p>
<p><code>firebasedatabase. instances. update</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam.serviceAccounts.signBlob</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub. subscriptions. getIamPolicy</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub. subscriptions. setIamPolicy</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
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
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.configurations.*</code></p>
<ul>
<li><code>run.configurations.get</code></li>
<li><code>run.configurations.list</code></li>
</ul>
<p><code>run.executions.*</code></p>
<ul>
<li><code>run.executions.cancel</code></li>
<li><code>run.executions.delete</code></li>
<li><code>run.executions.get</code></li>
<li><code>run.executions.list</code></li>
</ul>
<p><code>run.instances.create</code></p>
<p><code>run.instances.delete</code></p>
<p><code>run.instances.get</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.invoke</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.instances.sshRead</code></p>
<p><code>run.instances.sshRoot</code></p>
<p><code>run.instances.start</code></p>
<p><code>run.instances.stop</code></p>
<p><code>run.instances.update</code></p>
<p><code>run.jobs.create</code></p>
<p><code>run.jobs.delete</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.jobs.run</code></p>
<p><code>run.jobs.runWithOverrides</code></p>
<p><code>run.jobs.sshRead</code></p>
<p><code>run.jobs.sshRoot</code></p>
<p><code>run.jobs.update</code></p>
<p><code>run.locations.*</code></p>
<ul>
<li><code>run.locations.list</code></li>
<li><code>run.locations.uploadSource</code></li>
</ul>
<p><code>run.operations.*</code></p>
<ul>
<li><code>run.operations.delete</code></li>
<li><code>run.operations.get</code></li>
<li><code>run.operations.list</code></li>
</ul>
<p><code>run.prompts.get</code></p>
<p><code>run.revisions.*</code></p>
<ul>
<li><code>run.revisions.delete</code></li>
<li><code>run.revisions.get</code></li>
<li><code>run.revisions.list</code></li>
</ul>
<p><code>run.routes.*</code></p>
<ul>
<li><code>run.routes.get</code></li>
<li><code>run.routes.invoke</code></li>
<li><code>run.routes.list</code></li>
</ul>
<p><code>run.services.create</code></p>
<p><code>run.services.delete</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>run.services.sshRead</code></p>
<p><code>run.services.sshRoot</code></p>
<p><code>run.services.update</code></p>
<p><code>run.tasks.*</code></p>
<ul>
<li><code>run.tasks.get</code></li>
<li><code>run.tasks.list</code></li>
</ul>
<p><code>run.workerpools.create</code></p>
<p><code>run.workerpools.delete</code></p>
<p><code>run.workerpools.get</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>run.workerpools.sshRead</code></p>
<p><code>run.workerpools.sshRoot</code></p>
<p><code>run.workerpools.update</code></p>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.disable</code></p>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>source.repos.get</code></p>
<p><code>source.repos.list</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>vpcaccess.connectors.get</code></p></td>
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
<td><code>cloudfunctions.functions.call</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudfunctions. functions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions. functions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudfunctions. functions. generationUpgrade</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions.functions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudfunctions. functions. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions. functions. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.invoker">Cloud Functions Invoker</a> ( <code>roles/ cloudfunctions.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a> ( <code>roles/ identitytoolkit.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudfunctions.functions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions. functions. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudfunctions. functions. sourceCodeGet</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions. functions. sourceCodeSet</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudfunctions. functions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudfunctions.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>cloudfunctions.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
