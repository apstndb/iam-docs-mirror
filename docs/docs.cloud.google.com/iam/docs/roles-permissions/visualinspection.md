---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/visualinspection
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection
title: Visual Inspection AI roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Visual Inspection AI. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Visual Inspection AI roles

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
<td>Visual Inspection AI Admin
<p>( <code>roles/ visualinspection.admin</code> )</p>
<p>Admin role for Visual Inspection AI</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>visualinspection.*</code></p>
<ul>
<li><code>visualinspection. annotationSets. create</code></li>
<li><code>visualinspection. annotationSets. delete</code></li>
<li><code>visualinspection. annotationSets. get</code></li>
<li><code>visualinspection. annotationSets. list</code></li>
<li><code>visualinspection. annotationSets. update</code></li>
<li><code>visualinspection. annotationSpecs. create</code></li>
<li><code>visualinspection. annotationSpecs. delete</code></li>
<li><code>visualinspection. annotationSpecs. get</code></li>
<li><code>visualinspection. annotationSpecs. list</code></li>
<li><code>visualinspection. annotations. create</code></li>
<li><code>visualinspection. annotations. delete</code></li>
<li><code>visualinspection. annotations. get</code></li>
<li><code>visualinspection. annotations. list</code></li>
<li><code>visualinspection. annotations. update</code></li>
<li><code>visualinspection. datasets. create</code></li>
<li><code>visualinspection. datasets. delete</code></li>
<li><code>visualinspection. datasets. export</code></li>
<li><code>visualinspection.datasets.get</code></li>
<li><code>visualinspection. datasets. import</code></li>
<li><code>visualinspection.datasets.list</code></li>
<li><code>visualinspection. datasets. update</code></li>
<li><code>visualinspection.images.delete</code></li>
<li><code>visualinspection.images.get</code></li>
<li><code>visualinspection.images.list</code></li>
<li><code>visualinspection.images.update</code></li>
<li><code>visualinspection.locations.get</code></li>
<li><code>visualinspection. locations. list</code></li>
<li><code>visualinspection. locations. reportUsageMetrics</code></li>
<li><code>visualinspection. modelEvaluations. get</code></li>
<li><code>visualinspection. modelEvaluations. list</code></li>
<li><code>visualinspection.models.create</code></li>
<li><code>visualinspection.models.delete</code></li>
<li><code>visualinspection.models.get</code></li>
<li><code>visualinspection.models.list</code></li>
<li><code>visualinspection.models.update</code></li>
<li><code>visualinspection. models. writePrediction</code></li>
<li><code>visualinspection. modules. create</code></li>
<li><code>visualinspection. modules. delete</code></li>
<li><code>visualinspection.modules.get</code></li>
<li><code>visualinspection.modules.list</code></li>
<li><code>visualinspection. modules. update</code></li>
<li><code>visualinspection. operations. get</code></li>
<li><code>visualinspection. operations. list</code></li>
<li><code>visualinspection. solutionArtifacts. create</code></li>
<li><code>visualinspection. solutionArtifacts. delete</code></li>
<li><code>visualinspection. solutionArtifacts. get</code></li>
<li><code>visualinspection. solutionArtifacts. list</code></li>
<li><code>visualinspection. solutionArtifacts. predict</code></li>
<li><code>visualinspection. solutionArtifacts. update</code></li>
<li><code>visualinspection. solutions. create</code></li>
<li><code>visualinspection. solutions. delete</code></li>
<li><code>visualinspection.solutions.get</code></li>
<li><code>visualinspection. solutions. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Visual Inspection AI Solution Editor
<p>( <code>roles/ visualinspection.editor</code> )</p>
<p>Read and write access to all Visual Inspection AI resources except visualinspection.locations.reportUsageMetrics</p></td>
<td><p><code>visualinspection. annotationSets.*</code></p>
<ul>
<li><code>visualinspection. annotationSets. create</code></li>
<li><code>visualinspection. annotationSets. delete</code></li>
<li><code>visualinspection. annotationSets. get</code></li>
<li><code>visualinspection. annotationSets. list</code></li>
<li><code>visualinspection. annotationSets. update</code></li>
</ul>
<p><code>visualinspection. annotationSpecs.*</code></p>
<ul>
<li><code>visualinspection. annotationSpecs. create</code></li>
<li><code>visualinspection. annotationSpecs. delete</code></li>
<li><code>visualinspection. annotationSpecs. get</code></li>
<li><code>visualinspection. annotationSpecs. list</code></li>
</ul>
<p><code>visualinspection.annotations.*</code></p>
<ul>
<li><code>visualinspection. annotations. create</code></li>
<li><code>visualinspection. annotations. delete</code></li>
<li><code>visualinspection. annotations. get</code></li>
<li><code>visualinspection. annotations. list</code></li>
<li><code>visualinspection. annotations. update</code></li>
</ul>
<p><code>visualinspection.datasets.*</code></p>
<ul>
<li><code>visualinspection. datasets. create</code></li>
<li><code>visualinspection. datasets. delete</code></li>
<li><code>visualinspection. datasets. export</code></li>
<li><code>visualinspection.datasets.get</code></li>
<li><code>visualinspection. datasets. import</code></li>
<li><code>visualinspection.datasets.list</code></li>
<li><code>visualinspection. datasets. update</code></li>
</ul>
<p><code>visualinspection.images.*</code></p>
<ul>
<li><code>visualinspection.images.delete</code></li>
<li><code>visualinspection.images.get</code></li>
<li><code>visualinspection.images.list</code></li>
<li><code>visualinspection.images.update</code></li>
</ul>
<p><code>visualinspection.locations.get</code></p>
<p><code>visualinspection. locations. list</code></p>
<p><code>visualinspection. modelEvaluations.*</code></p>
<ul>
<li><code>visualinspection. modelEvaluations. get</code></li>
<li><code>visualinspection. modelEvaluations. list</code></li>
</ul>
<p><code>visualinspection.models.*</code></p>
<ul>
<li><code>visualinspection.models.create</code></li>
<li><code>visualinspection.models.delete</code></li>
<li><code>visualinspection.models.get</code></li>
<li><code>visualinspection.models.list</code></li>
<li><code>visualinspection.models.update</code></li>
<li><code>visualinspection. models. writePrediction</code></li>
</ul>
<p><code>visualinspection.modules.*</code></p>
<ul>
<li><code>visualinspection. modules. create</code></li>
<li><code>visualinspection. modules. delete</code></li>
<li><code>visualinspection.modules.get</code></li>
<li><code>visualinspection.modules.list</code></li>
<li><code>visualinspection. modules. update</code></li>
</ul>
<p><code>visualinspection.operations.*</code></p>
<ul>
<li><code>visualinspection. operations. get</code></li>
<li><code>visualinspection. operations. list</code></li>
</ul>
<p><code>visualinspection. solutionArtifacts.*</code></p>
<ul>
<li><code>visualinspection. solutionArtifacts. create</code></li>
<li><code>visualinspection. solutionArtifacts. delete</code></li>
<li><code>visualinspection. solutionArtifacts. get</code></li>
<li><code>visualinspection. solutionArtifacts. list</code></li>
<li><code>visualinspection. solutionArtifacts. predict</code></li>
<li><code>visualinspection. solutionArtifacts. update</code></li>
</ul>
<p><code>visualinspection.solutions.*</code></p>
<ul>
<li><code>visualinspection. solutions. create</code></li>
<li><code>visualinspection. solutions. delete</code></li>
<li><code>visualinspection.solutions.get</code></li>
<li><code>visualinspection. solutions. list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Visual Inspection AI Viewer
<p>( <code>roles/ visualinspection.viewer</code> )</p>
<p>Read access to Visual Inspection AI resources</p></td>
<td><p><code>visualinspection. annotationSets. get</code></p>
<p><code>visualinspection. annotationSets. list</code></p>
<p><code>visualinspection. annotationSpecs. get</code></p>
<p><code>visualinspection. annotationSpecs. list</code></p>
<p><code>visualinspection. annotations. get</code></p>
<p><code>visualinspection. annotations. list</code></p>
<p><code>visualinspection. datasets. export</code></p>
<p><code>visualinspection.datasets.get</code></p>
<p><code>visualinspection.datasets.list</code></p>
<p><code>visualinspection.images.get</code></p>
<p><code>visualinspection.images.list</code></p>
<p><code>visualinspection.locations.get</code></p>
<p><code>visualinspection. locations. list</code></p>
<p><code>visualinspection. modelEvaluations.*</code></p>
<ul>
<li><code>visualinspection. modelEvaluations. get</code></li>
<li><code>visualinspection. modelEvaluations. list</code></li>
</ul>
<p><code>visualinspection.models.get</code></p>
<p><code>visualinspection.models.list</code></p>
<p><code>visualinspection.modules.get</code></p>
<p><code>visualinspection.modules.list</code></p>
<p><code>visualinspection.operations.*</code></p>
<ul>
<li><code>visualinspection. operations. get</code></li>
<li><code>visualinspection. operations. list</code></li>
</ul>
<p><code>visualinspection. solutionArtifacts. get</code></p>
<p><code>visualinspection. solutionArtifacts. list</code></p>
<p><code>visualinspection. solutionArtifacts. predict</code></p>
<p><code>visualinspection.solutions.get</code></p>
<p><code>visualinspection. solutions. list</code></p></td>
</tr>
<tr class="even">
<td>Visual Inspection AI Usage Metrics Reporter
<p>( <code>roles/ visualinspection.usageMetricsReporter</code> )</p>
<p>ReportUsageMetric access to Visual Inspection AI Service</p></td>
<td><p><code>visualinspection. locations. reportUsageMetrics</code></p></td>
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
<td>Visual Inspection AI Service Agent
<p>( <code>roles/ visualinspection.serviceAgent</code> )</p>
<p>Grants Visual Inspection AI Service Agent admin roles for accessing/exporting training data, pushing containers artifacts to GCR and ArtifactsRegistry, and Vertex AI for storing data and running training jobs.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.*</code></p>
<ul>
<li><code>aiplatform. agentAnomalyDetectionScopes. create</code></li>
<li><code>aiplatform. agentAnomalyDetectionScopes. delete</code></li>
<li><code>aiplatform. agentAnomalyDetectionScopes. get</code></li>
<li><code>aiplatform. agentAnomalyDetectionScopes. list</code></li>
<li><code>aiplatform. agentExamples. create</code></li>
<li><code>aiplatform. agentExamples. delete</code></li>
<li><code>aiplatform.agentExamples.get</code></li>
<li><code>aiplatform.agentExamples.list</code></li>
<li><code>aiplatform. agentExamples. update</code></li>
<li><code>aiplatform.agents.create</code></li>
<li><code>aiplatform.agents.delete</code></li>
<li><code>aiplatform.agents.get</code></li>
<li><code>aiplatform.agents.list</code></li>
<li><code>aiplatform.agents.update</code></li>
<li><code>aiplatform. analyzedInvocations. get</code></li>
<li><code>aiplatform. analyzedInvocations. list</code></li>
<li><code>aiplatform. analyzedSessions. aggregate</code></li>
<li><code>aiplatform. analyzedSessions. get</code></li>
<li><code>aiplatform. analyzedSessions. list</code></li>
<li><code>aiplatform. annotationSpecs. create</code></li>
<li><code>aiplatform. annotationSpecs. delete</code></li>
<li><code>aiplatform.annotationSpecs.get</code></li>
<li><code>aiplatform. annotationSpecs. list</code></li>
<li><code>aiplatform. annotationSpecs. update</code></li>
<li><code>aiplatform.annotations.create</code></li>
<li><code>aiplatform.annotations.delete</code></li>
<li><code>aiplatform.annotations.get</code></li>
<li><code>aiplatform.annotations.list</code></li>
<li><code>aiplatform.annotations.update</code></li>
<li><code>aiplatform.apps.create</code></li>
<li><code>aiplatform.apps.delete</code></li>
<li><code>aiplatform.apps.get</code></li>
<li><code>aiplatform.apps.list</code></li>
<li><code>aiplatform.apps.update</code></li>
<li><code>aiplatform.artifacts.create</code></li>
<li><code>aiplatform.artifacts.delete</code></li>
<li><code>aiplatform.artifacts.get</code></li>
<li><code>aiplatform.artifacts.list</code></li>
<li><code>aiplatform.artifacts.update</code></li>
<li><code>aiplatform. batchPredictionJobs. cancel</code></li>
<li><code>aiplatform. batchPredictionJobs. create</code></li>
<li><code>aiplatform. batchPredictionJobs. delete</code></li>
<li><code>aiplatform. batchPredictionJobs. get</code></li>
<li><code>aiplatform. batchPredictionJobs. list</code></li>
<li><code>aiplatform.cacheConfigs.get</code></li>
<li><code>aiplatform.cacheConfigs.update</code></li>
<li><code>aiplatform. cachedContents. create</code></li>
<li><code>aiplatform. cachedContents. delete</code></li>
<li><code>aiplatform.cachedContents.get</code></li>
<li><code>aiplatform.cachedContents.list</code></li>
<li><code>aiplatform. cachedContents. update</code></li>
<li><code>aiplatform.consents.get</code></li>
<li><code>aiplatform.consents.update</code></li>
<li><code>aiplatform. contexts. addContextArtifactsAndExecutions</code></li>
<li><code>aiplatform. contexts. addContextChildren</code></li>
<li><code>aiplatform.contexts.create</code></li>
<li><code>aiplatform.contexts.delete</code></li>
<li><code>aiplatform.contexts.get</code></li>
<li><code>aiplatform.contexts.list</code></li>
<li><code>aiplatform. contexts. queryContextLineageSubgraph</code></li>
<li><code>aiplatform.contexts.update</code></li>
<li><code>aiplatform.customJobs.cancel</code></li>
<li><code>aiplatform.customJobs.create</code></li>
<li><code>aiplatform.customJobs.delete</code></li>
<li><code>aiplatform.customJobs.get</code></li>
<li><code>aiplatform.customJobs.list</code></li>
<li><code>aiplatform.dataItems.create</code></li>
<li><code>aiplatform.dataItems.delete</code></li>
<li><code>aiplatform.dataItems.get</code></li>
<li><code>aiplatform.dataItems.list</code></li>
<li><code>aiplatform.dataItems.update</code></li>
<li><code>aiplatform. dataLabelingJobs. cancel</code></li>
<li><code>aiplatform. dataLabelingJobs. create</code></li>
<li><code>aiplatform. dataLabelingJobs. delete</code></li>
<li><code>aiplatform. dataLabelingJobs. get</code></li>
<li><code>aiplatform. dataLabelingJobs. list</code></li>
<li><code>aiplatform. datasetVersions. create</code></li>
<li><code>aiplatform. datasetVersions. delete</code></li>
<li><code>aiplatform.datasetVersions.get</code></li>
<li><code>aiplatform. datasetVersions. list</code></li>
<li><code>aiplatform. datasetVersions. restore</code></li>
<li><code>aiplatform.datasets.create</code></li>
<li><code>aiplatform.datasets.delete</code></li>
<li><code>aiplatform.datasets.export</code></li>
<li><code>aiplatform.datasets.get</code></li>
<li><code>aiplatform.datasets.import</code></li>
<li><code>aiplatform.datasets.list</code></li>
<li><code>aiplatform.datasets.update</code></li>
<li><code>aiplatform. deploymentResourcePools. create</code></li>
<li><code>aiplatform. deploymentResourcePools. delete</code></li>
<li><code>aiplatform. deploymentResourcePools. get</code></li>
<li><code>aiplatform. deploymentResourcePools. list</code></li>
<li><code>aiplatform. deploymentResourcePools. queryDeployedModels</code></li>
<li><code>aiplatform. deploymentResourcePools. update</code></li>
<li><code>aiplatform. edgeDeploymentJobs. create</code></li>
<li><code>aiplatform. edgeDeploymentJobs. delete</code></li>
<li><code>aiplatform. edgeDeploymentJobs. get</code></li>
<li><code>aiplatform. edgeDeploymentJobs. list</code></li>
<li><code>aiplatform. edgeDeviceDebugInfo. get</code></li>
<li><code>aiplatform.edgeDevices.create</code></li>
<li><code>aiplatform.edgeDevices.delete</code></li>
<li><code>aiplatform.edgeDevices.get</code></li>
<li><code>aiplatform.edgeDevices.list</code></li>
<li><code>aiplatform.edgeDevices.update</code></li>
<li><code>aiplatform.endpoints.create</code></li>
<li><code>aiplatform.endpoints.delete</code></li>
<li><code>aiplatform.endpoints.deploy</code></li>
<li><code>aiplatform.endpoints.explain</code></li>
<li><code>aiplatform.endpoints.get</code></li>
<li><code>aiplatform. endpoints. getIamPolicy</code></li>
<li><code>aiplatform.endpoints.list</code></li>
<li><code>aiplatform.endpoints.predict</code></li>
<li><code>aiplatform. endpoints. setIamPolicy</code></li>
<li><code>aiplatform.endpoints.undeploy</code></li>
<li><code>aiplatform.endpoints.update</code></li>
<li><code>aiplatform.entityTypes.create</code></li>
<li><code>aiplatform.entityTypes.delete</code></li>
<li><code>aiplatform. entityTypes. deleteFeatureValues</code></li>
<li><code>aiplatform. entityTypes. exportFeatureValues</code></li>
<li><code>aiplatform.entityTypes.get</code></li>
<li><code>aiplatform. entityTypes. getIamPolicy</code></li>
<li><code>aiplatform. entityTypes. importFeatureValues</code></li>
<li><code>aiplatform.entityTypes.list</code></li>
<li><code>aiplatform. entityTypes. readFeatureValues</code></li>
<li><code>aiplatform. entityTypes. setIamPolicy</code></li>
<li><code>aiplatform. entityTypes. streamingReadFeatureValues</code></li>
<li><code>aiplatform.entityTypes.update</code></li>
<li><code>aiplatform. entityTypes. writeFeatureValues</code></li>
<li><code>aiplatform. evaluationExperiments. create</code></li>
<li><code>aiplatform. evaluationExperiments. delete</code></li>
<li><code>aiplatform. evaluationExperiments. get</code></li>
<li><code>aiplatform. evaluationExperiments. list</code></li>
<li><code>aiplatform. evaluationExperiments. update</code></li>
<li><code>aiplatform. evaluationItems. create</code></li>
<li><code>aiplatform. evaluationItems. delete</code></li>
<li><code>aiplatform.evaluationItems.get</code></li>
<li><code>aiplatform. evaluationItems. list</code></li>
<li><code>aiplatform. evaluationItems. update</code></li>
<li><code>aiplatform. evaluationMetrics. create</code></li>
<li><code>aiplatform. evaluationMetrics. delete</code></li>
<li><code>aiplatform. evaluationMetrics. get</code></li>
<li><code>aiplatform. evaluationMetrics. list</code></li>
<li><code>aiplatform. evaluationRuns. cancel</code></li>
<li><code>aiplatform. evaluationRuns. create</code></li>
<li><code>aiplatform. evaluationRuns. delete</code></li>
<li><code>aiplatform. evaluationRuns. execute</code></li>
<li><code>aiplatform.evaluationRuns.get</code></li>
<li><code>aiplatform.evaluationRuns.list</code></li>
<li><code>aiplatform. evaluationRuns. update</code></li>
<li><code>aiplatform. evaluationSets. create</code></li>
<li><code>aiplatform. evaluationSets. delete</code></li>
<li><code>aiplatform.evaluationSets.get</code></li>
<li><code>aiplatform. evaluationSets. import</code></li>
<li><code>aiplatform.evaluationSets.list</code></li>
<li><code>aiplatform. evaluationSets. update</code></li>
<li><code>aiplatform. exampleStores. create</code></li>
<li><code>aiplatform. exampleStores. delete</code></li>
<li><code>aiplatform.exampleStores.get</code></li>
<li><code>aiplatform.exampleStores.list</code></li>
<li><code>aiplatform. exampleStores. readExample</code></li>
<li><code>aiplatform. exampleStores. update</code></li>
<li><code>aiplatform. exampleStores. writeExample</code></li>
<li><code>aiplatform. executions. addExecutionEvents</code></li>
<li><code>aiplatform.executions.create</code></li>
<li><code>aiplatform.executions.delete</code></li>
<li><code>aiplatform.executions.get</code></li>
<li><code>aiplatform.executions.list</code></li>
<li><code>aiplatform. executions. queryExecutionInputsAndOutputs</code></li>
<li><code>aiplatform.executions.update</code></li>
<li><code>aiplatform.extensions.delete</code></li>
<li><code>aiplatform.extensions.execute</code></li>
<li><code>aiplatform.extensions.get</code></li>
<li><code>aiplatform.extensions.import</code></li>
<li><code>aiplatform.extensions.list</code></li>
<li><code>aiplatform.extensions.update</code></li>
<li><code>aiplatform. featureGroups. create</code></li>
<li><code>aiplatform. featureGroups. delete</code></li>
<li><code>aiplatform.featureGroups.get</code></li>
<li><code>aiplatform. featureGroups. getIamPolicy</code></li>
<li><code>aiplatform.featureGroups.list</code></li>
<li><code>aiplatform. featureGroups. setIamPolicy</code></li>
<li><code>aiplatform. featureGroups. update</code></li>
<li><code>aiplatform. featureMonitorJobs. create</code></li>
<li><code>aiplatform. featureMonitorJobs. get</code></li>
<li><code>aiplatform. featureMonitorJobs. list</code></li>
<li><code>aiplatform. featureMonitors. create</code></li>
<li><code>aiplatform. featureMonitors. delete</code></li>
<li><code>aiplatform.featureMonitors.get</code></li>
<li><code>aiplatform. featureMonitors. list</code></li>
<li><code>aiplatform. featureMonitors. update</code></li>
<li><code>aiplatform. featureOnlineStores. create</code></li>
<li><code>aiplatform. featureOnlineStores. delete</code></li>
<li><code>aiplatform. featureOnlineStores. get</code></li>
<li><code>aiplatform. featureOnlineStores. getIamPolicy</code></li>
<li><code>aiplatform. featureOnlineStores. list</code></li>
<li><code>aiplatform. featureOnlineStores. setIamPolicy</code></li>
<li><code>aiplatform. featureOnlineStores. update</code></li>
<li><code>aiplatform. featureViewSyncs. get</code></li>
<li><code>aiplatform. featureViewSyncs. list</code></li>
<li><code>aiplatform.featureViews.create</code></li>
<li><code>aiplatform.featureViews.delete</code></li>
<li><code>aiplatform. featureViews. directWrite</code></li>
<li><code>aiplatform. featureViews. fetchFeatureValues</code></li>
<li><code>aiplatform.featureViews.get</code></li>
<li><code>aiplatform. featureViews. getIamPolicy</code></li>
<li><code>aiplatform.featureViews.list</code></li>
<li><code>aiplatform. featureViews. searchNearestEntities</code></li>
<li><code>aiplatform. featureViews. setIamPolicy</code></li>
<li><code>aiplatform.featureViews.sync</code></li>
<li><code>aiplatform.featureViews.update</code></li>
<li><code>aiplatform.features.create</code></li>
<li><code>aiplatform.features.delete</code></li>
<li><code>aiplatform.features.get</code></li>
<li><code>aiplatform.features.list</code></li>
<li><code>aiplatform.features.update</code></li>
<li><code>aiplatform. featurestores. batchReadFeatureValues</code></li>
<li><code>aiplatform. featurestores. create</code></li>
<li><code>aiplatform. featurestores. delete</code></li>
<li><code>aiplatform. featurestores. exportFeatures</code></li>
<li><code>aiplatform.featurestores.get</code></li>
<li><code>aiplatform. featurestores. getIamPolicy</code></li>
<li><code>aiplatform. featurestores. importFeatures</code></li>
<li><code>aiplatform.featurestores.list</code></li>
<li><code>aiplatform. featurestores. readFeatures</code></li>
<li><code>aiplatform. featurestores. setIamPolicy</code></li>
<li><code>aiplatform. featurestores. update</code></li>
<li><code>aiplatform. featurestores. writeFeatures</code></li>
<li><code>aiplatform. humanInTheLoops. cancel</code></li>
<li><code>aiplatform. humanInTheLoops. create</code></li>
<li><code>aiplatform. humanInTheLoops. delete</code></li>
<li><code>aiplatform.humanInTheLoops.get</code></li>
<li><code>aiplatform. humanInTheLoops. list</code></li>
<li><code>aiplatform. humanInTheLoops. queryAnnotationStats</code></li>
<li><code>aiplatform. humanInTheLoops. send</code></li>
<li><code>aiplatform. humanInTheLoops. update</code></li>
<li><code>aiplatform. hyperparameterTuningJobs. cancel</code></li>
<li><code>aiplatform. hyperparameterTuningJobs. create</code></li>
<li><code>aiplatform. hyperparameterTuningJobs. delete</code></li>
<li><code>aiplatform. hyperparameterTuningJobs. get</code></li>
<li><code>aiplatform. hyperparameterTuningJobs. list</code></li>
<li><code>aiplatform. indexEndpoints. create</code></li>
<li><code>aiplatform. indexEndpoints. delete</code></li>
<li><code>aiplatform. indexEndpoints. deploy</code></li>
<li><code>aiplatform.indexEndpoints.get</code></li>
<li><code>aiplatform.indexEndpoints.list</code></li>
<li><code>aiplatform. indexEndpoints. queryVectors</code></li>
<li><code>aiplatform. indexEndpoints. undeploy</code></li>
<li><code>aiplatform. indexEndpoints. update</code></li>
<li><code>aiplatform.indexes.create</code></li>
<li><code>aiplatform.indexes.delete</code></li>
<li><code>aiplatform.indexes.get</code></li>
<li><code>aiplatform.indexes.list</code></li>
<li><code>aiplatform.indexes.update</code></li>
<li><code>aiplatform.interactions.cancel</code></li>
<li><code>aiplatform.interactions.create</code></li>
<li><code>aiplatform.interactions.delete</code></li>
<li><code>aiplatform.interactions.get</code></li>
<li><code>aiplatform.interactions.list</code></li>
<li><code>aiplatform. locations. evaluateInstances</code></li>
<li><code>aiplatform.locations.get</code></li>
<li><code>aiplatform.locations.list</code></li>
<li><code>aiplatform.memories.create</code></li>
<li><code>aiplatform.memories.delete</code></li>
<li><code>aiplatform.memories.generate</code></li>
<li><code>aiplatform.memories.get</code></li>
<li><code>aiplatform.memories.list</code></li>
<li><code>aiplatform.memories.retrieve</code></li>
<li><code>aiplatform.memories.update</code></li>
<li><code>aiplatform.memoryRevisions.get</code></li>
<li><code>aiplatform. memoryRevisions. list</code></li>
<li><code>aiplatform. memoryRevisions. rollback</code></li>
<li><code>aiplatform. metadataSchemas. create</code></li>
<li><code>aiplatform. metadataSchemas. delete</code></li>
<li><code>aiplatform.metadataSchemas.get</code></li>
<li><code>aiplatform. metadataSchemas. list</code></li>
<li><code>aiplatform. metadataStores. create</code></li>
<li><code>aiplatform. metadataStores. delete</code></li>
<li><code>aiplatform.metadataStores.get</code></li>
<li><code>aiplatform.metadataStores.list</code></li>
<li><code>aiplatform. migratableResources. migrate</code></li>
<li><code>aiplatform. migratableResources. search</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. create</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. delete</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. get</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. list</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. pause</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. resume</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. searchStatsAnomalies</code></li>
<li><code>aiplatform. modelDeploymentMonitoringJobs. update</code></li>
<li><code>aiplatform. modelEvaluationSlices. get</code></li>
<li><code>aiplatform. modelEvaluationSlices. import</code></li>
<li><code>aiplatform. modelEvaluationSlices. list</code></li>
<li><code>aiplatform. modelEvaluations. exportEvaluatedDataItems</code></li>
<li><code>aiplatform. modelEvaluations. get</code></li>
<li><code>aiplatform. modelEvaluations. import</code></li>
<li><code>aiplatform. modelEvaluations. list</code></li>
<li><code>aiplatform. modelMonitoringJobs. create</code></li>
<li><code>aiplatform. modelMonitoringJobs. delete</code></li>
<li><code>aiplatform. modelMonitoringJobs. get</code></li>
<li><code>aiplatform. modelMonitoringJobs. list</code></li>
<li><code>aiplatform. modelMonitors. create</code></li>
<li><code>aiplatform. modelMonitors. delete</code></li>
<li><code>aiplatform.modelMonitors.get</code></li>
<li><code>aiplatform.modelMonitors.list</code></li>
<li><code>aiplatform. modelMonitors. searchModelMonitoringAlerts</code></li>
<li><code>aiplatform. modelMonitors. searchModelMonitoringStats</code></li>
<li><code>aiplatform. modelMonitors. update</code></li>
<li><code>aiplatform.models.delete</code></li>
<li><code>aiplatform.models.export</code></li>
<li><code>aiplatform.models.get</code></li>
<li><code>aiplatform.models.list</code></li>
<li><code>aiplatform.models.update</code></li>
<li><code>aiplatform.models.upload</code></li>
<li><code>aiplatform. monitoredAgents. clearTrainingData</code></li>
<li><code>aiplatform. monitoredAgents. disable</code></li>
<li><code>aiplatform. monitoredAgents. enable</code></li>
<li><code>aiplatform.monitoredAgents.get</code></li>
<li><code>aiplatform. monitoredAgents. list</code></li>
<li><code>aiplatform.nasJobs.cancel</code></li>
<li><code>aiplatform.nasJobs.create</code></li>
<li><code>aiplatform.nasJobs.delete</code></li>
<li><code>aiplatform.nasJobs.get</code></li>
<li><code>aiplatform.nasJobs.list</code></li>
<li><code>aiplatform.nasTrialDetails.get</code></li>
<li><code>aiplatform. nasTrialDetails. list</code></li>
<li><code>aiplatform. notebookExecutionJobs. create</code></li>
<li><code>aiplatform. notebookExecutionJobs. delete</code></li>
<li><code>aiplatform. notebookExecutionJobs. get</code></li>
<li><code>aiplatform. notebookExecutionJobs. list</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. apply</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. create</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. delete</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. get</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. getIamPolicy</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. list</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. setDefault</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. setIamPolicy</code></li>
<li><code>aiplatform. notebookRuntimeTemplates. update</code></li>
<li><code>aiplatform. notebookRuntimes. assign</code></li>
<li><code>aiplatform. notebookRuntimes. delete</code></li>
<li><code>aiplatform. notebookRuntimes. get</code></li>
<li><code>aiplatform. notebookRuntimes. list</code></li>
<li><code>aiplatform. notebookRuntimes. start</code></li>
<li><code>aiplatform. notebookRuntimes. update</code></li>
<li><code>aiplatform. notebookRuntimes. upgrade</code></li>
<li><code>aiplatform. onlineEvaluators. create</code></li>
<li><code>aiplatform. onlineEvaluators. delete</code></li>
<li><code>aiplatform. onlineEvaluators. get</code></li>
<li><code>aiplatform. onlineEvaluators. list</code></li>
<li><code>aiplatform. onlineEvaluators. update</code></li>
<li><code>aiplatform.operations.list</code></li>
<li><code>aiplatform. persistentResources. create</code></li>
<li><code>aiplatform. persistentResources. delete</code></li>
<li><code>aiplatform. persistentResources. get</code></li>
<li><code>aiplatform. persistentResources. list</code></li>
<li><code>aiplatform.pipelineJobs.cancel</code></li>
<li><code>aiplatform.pipelineJobs.create</code></li>
<li><code>aiplatform.pipelineJobs.delete</code></li>
<li><code>aiplatform.pipelineJobs.get</code></li>
<li><code>aiplatform.pipelineJobs.list</code></li>
<li><code>aiplatform. provisionedThroughputRevisions. get</code></li>
<li><code>aiplatform. provisionedThroughputRevisions. list</code></li>
<li><code>aiplatform. provisionedThroughputs. cancel</code></li>
<li><code>aiplatform. provisionedThroughputs. changeScope</code></li>
<li><code>aiplatform. provisionedThroughputs. create</code></li>
<li><code>aiplatform. provisionedThroughputs. get</code></li>
<li><code>aiplatform. provisionedThroughputs. list</code></li>
<li><code>aiplatform. provisionedThroughputs. split</code></li>
<li><code>aiplatform. provisionedThroughputs. update</code></li>
<li><code>aiplatform.ragCorpora.create</code></li>
<li><code>aiplatform.ragCorpora.delete</code></li>
<li><code>aiplatform.ragCorpora.get</code></li>
<li><code>aiplatform.ragCorpora.list</code></li>
<li><code>aiplatform.ragCorpora.query</code></li>
<li><code>aiplatform.ragCorpora.update</code></li>
<li><code>aiplatform. ragEngineConfigs. get</code></li>
<li><code>aiplatform. ragEngineConfigs. update</code></li>
<li><code>aiplatform.ragFiles.delete</code></li>
<li><code>aiplatform.ragFiles.get</code></li>
<li><code>aiplatform.ragFiles.import</code></li>
<li><code>aiplatform.ragFiles.list</code></li>
<li><code>aiplatform.ragFiles.upload</code></li>
<li><code>aiplatform. reasoningEngineRuntimeRevisions. delete</code></li>
<li><code>aiplatform. reasoningEngineRuntimeRevisions. get</code></li>
<li><code>aiplatform. reasoningEngineRuntimeRevisions. list</code></li>
<li><code>aiplatform. reasoningEngineRuntimeRevisions. query</code></li>
<li><code>aiplatform. reasoningEngines. create</code></li>
<li><code>aiplatform. reasoningEngines. delete</code></li>
<li><code>aiplatform. reasoningEngines. get</code></li>
<li><code>aiplatform. reasoningEngines. getIamPolicy</code></li>
<li><code>aiplatform. reasoningEngines. list</code></li>
<li><code>aiplatform. reasoningEngines. query</code></li>
<li><code>aiplatform. reasoningEngines. setIamPolicy</code></li>
<li><code>aiplatform. reasoningEngines. update</code></li>
<li><code>aiplatform. sandboxEnvironments. create</code></li>
<li><code>aiplatform. sandboxEnvironments. delete</code></li>
<li><code>aiplatform. sandboxEnvironments. execute</code></li>
<li><code>aiplatform. sandboxEnvironments. get</code></li>
<li><code>aiplatform. sandboxEnvironments. list</code></li>
<li><code>aiplatform.schedules.create</code></li>
<li><code>aiplatform.schedules.delete</code></li>
<li><code>aiplatform.schedules.get</code></li>
<li><code>aiplatform.schedules.list</code></li>
<li><code>aiplatform.schedules.update</code></li>
<li><code>aiplatform. semanticGovernancePolicies. create</code></li>
<li><code>aiplatform. semanticGovernancePolicies. delete</code></li>
<li><code>aiplatform. semanticGovernancePolicies. get</code></li>
<li><code>aiplatform. semanticGovernancePolicies. list</code></li>
<li><code>aiplatform. semanticGovernancePolicies. update</code></li>
<li><code>aiplatform. semanticGovernancePolicyEngine. get</code></li>
<li><code>aiplatform. semanticGovernancePolicyEngine. update</code></li>
<li><code>aiplatform. sessionEvents. append</code></li>
<li><code>aiplatform.sessionEvents.list</code></li>
<li><code>aiplatform.sessions.create</code></li>
<li><code>aiplatform.sessions.delete</code></li>
<li><code>aiplatform.sessions.get</code></li>
<li><code>aiplatform.sessions.list</code></li>
<li><code>aiplatform.sessions.run</code></li>
<li><code>aiplatform.sessions.update</code></li>
<li><code>aiplatform. specialistPools. create</code></li>
<li><code>aiplatform. specialistPools. delete</code></li>
<li><code>aiplatform.specialistPools.get</code></li>
<li><code>aiplatform. specialistPools. list</code></li>
<li><code>aiplatform. specialistPools. update</code></li>
<li><code>aiplatform.studies.create</code></li>
<li><code>aiplatform.studies.delete</code></li>
<li><code>aiplatform.studies.get</code></li>
<li><code>aiplatform.studies.list</code></li>
<li><code>aiplatform.studies.update</code></li>
<li><code>aiplatform.tasks.cancel</code></li>
<li><code>aiplatform.tasks.create</code></li>
<li><code>aiplatform.tasks.delete</code></li>
<li><code>aiplatform.tasks.get</code></li>
<li><code>aiplatform.tasks.list</code></li>
<li><code>aiplatform.tasks.update</code></li>
<li><code>aiplatform. tensorboardExperiments. create</code></li>
<li><code>aiplatform. tensorboardExperiments. delete</code></li>
<li><code>aiplatform. tensorboardExperiments. get</code></li>
<li><code>aiplatform. tensorboardExperiments. list</code></li>
<li><code>aiplatform. tensorboardExperiments. update</code></li>
<li><code>aiplatform. tensorboardExperiments. write</code></li>
<li><code>aiplatform. tensorboardRuns. batchCreate</code></li>
<li><code>aiplatform. tensorboardRuns. create</code></li>
<li><code>aiplatform. tensorboardRuns. delete</code></li>
<li><code>aiplatform.tensorboardRuns.get</code></li>
<li><code>aiplatform. tensorboardRuns. list</code></li>
<li><code>aiplatform. tensorboardRuns. update</code></li>
<li><code>aiplatform. tensorboardRuns. write</code></li>
<li><code>aiplatform. tensorboardTimeSeries. batchCreate</code></li>
<li><code>aiplatform. tensorboardTimeSeries. batchRead</code></li>
<li><code>aiplatform. tensorboardTimeSeries. create</code></li>
<li><code>aiplatform. tensorboardTimeSeries. delete</code></li>
<li><code>aiplatform. tensorboardTimeSeries. get</code></li>
<li><code>aiplatform. tensorboardTimeSeries. list</code></li>
<li><code>aiplatform. tensorboardTimeSeries. read</code></li>
<li><code>aiplatform. tensorboardTimeSeries. update</code></li>
<li><code>aiplatform.tensorboards.create</code></li>
<li><code>aiplatform.tensorboards.delete</code></li>
<li><code>aiplatform.tensorboards.get</code></li>
<li><code>aiplatform.tensorboards.list</code></li>
<li><code>aiplatform. tensorboards. recordAccess</code></li>
<li><code>aiplatform.tensorboards.update</code></li>
<li><code>aiplatform. trainingPipelines. cancel</code></li>
<li><code>aiplatform. trainingPipelines. create</code></li>
<li><code>aiplatform. trainingPipelines. delete</code></li>
<li><code>aiplatform. trainingPipelines. get</code></li>
<li><code>aiplatform. trainingPipelines. list</code></li>
<li><code>aiplatform.trials.create</code></li>
<li><code>aiplatform.trials.delete</code></li>
<li><code>aiplatform.trials.get</code></li>
<li><code>aiplatform.trials.list</code></li>
<li><code>aiplatform.trials.update</code></li>
<li><code>aiplatform.tuningJobs.cancel</code></li>
<li><code>aiplatform.tuningJobs.create</code></li>
<li><code>aiplatform.tuningJobs.delete</code></li>
<li><code>aiplatform.tuningJobs.get</code></li>
<li><code>aiplatform.tuningJobs.list</code></li>
<li><code>aiplatform. tuningJobs. optimizePrompt</code></li>
<li><code>aiplatform. tuningJobs. validateReinforcementTuningReward</code></li>
<li><code>aiplatform. tuningJobs. vertexTune</code></li>
</ul>
<p><code>artifactregistry. aptartifacts. create</code></p>
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
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>firebase.projects.get</code></p>
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

## Visual Inspection AI permissions

| Permission                                        | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `visualinspection. annotationSets. create`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotationSets. delete`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotationSets. get`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. annotationSets. list`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. annotationSets. update`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotationSpecs. create`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotationSpecs. delete`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotationSpecs. get`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. annotationSpecs. list`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. annotations. create`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotations. delete`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. annotations. get`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. annotations. list`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. annotations. update`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. datasets. create`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. datasets. delete`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. datasets. export`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection.datasets.get`                   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. datasets. import`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.datasets.list`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. datasets. update`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.images.delete`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.images.get`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection.images.list`                    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection.images.update`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.locations.get`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. locations. list`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. locations. reportUsageMetrics` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Visual Inspection AI Usage Metrics Reporter](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.usageMetricsReporter) ( `roles/ visualinspection.usageMetricsReporter` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `visualinspection. modelEvaluations. get`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. modelEvaluations. list`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection.models.create`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.models.delete`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.models.get`                     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection.models.list`                    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection.models.update`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. models. writePrediction`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. modules. create`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. modules. delete`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.modules.get`                    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection.modules.list`                   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. modules. update`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. operations. get`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. operations. list`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. solutionArtifacts. create`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. solutionArtifacts. delete`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. solutionArtifacts. get`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. solutionArtifacts. list`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `visualinspection. solutionArtifacts. predict`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. solutionArtifacts. update`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. solutions. create`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection. solutions. delete`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `visualinspection.solutions.get`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `visualinspection. solutions. list`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Visual Inspection AI Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin) ( `roles/ visualinspection.admin` ) [Visual Inspection AI Solution Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.editor) ( `roles/ visualinspection.editor` ) [Visual Inspection AI Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.viewer) ( `roles/ visualinspection.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
