---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/visionai
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/visionai
title: Vision AI roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Vision AI. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Vision AI roles

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
<td>VisionAI Admin <sup>Beta</sup>
<p>( <code>roles/ visionai.admin</code> )</p>
<p>Full access to Vision AI all resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>visionai.*</code></p>
<ul>
<li><code>visionai.analyses.create</code></li>
<li><code>visionai.analyses.delete</code></li>
<li><code>visionai.analyses.get</code></li>
<li><code>visionai.analyses.getIamPolicy</code></li>
<li><code>visionai.analyses.list</code></li>
<li><code>visionai.analyses.setIamPolicy</code></li>
<li><code>visionai.analyses.update</code></li>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
<li><code>visionai.applications.create</code></li>
<li><code>visionai.applications.delete</code></li>
<li><code>visionai.applications.deploy</code></li>
<li><code>visionai.applications.get</code></li>
<li><code>visionai.applications.list</code></li>
<li><code>visionai.applications.undeploy</code></li>
<li><code>visionai.applications.update</code></li>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
<li><code>visionai.clusters.create</code></li>
<li><code>visionai.clusters.delete</code></li>
<li><code>visionai.clusters.get</code></li>
<li><code>visionai.clusters.getIamPolicy</code></li>
<li><code>visionai.clusters.list</code></li>
<li><code>visionai.clusters.setIamPolicy</code></li>
<li><code>visionai.clusters.update</code></li>
<li><code>visionai.clusters.watch</code></li>
<li><code>visionai.corpora.analyze</code></li>
<li><code>visionai.corpora.create</code></li>
<li><code>visionai.corpora.delete</code></li>
<li><code>visionai.corpora.get</code></li>
<li><code>visionai.corpora.import</code></li>
<li><code>visionai.corpora.list</code></li>
<li><code>visionai.corpora.suggest</code></li>
<li><code>visionai.corpora.update</code></li>
<li><code>visionai.dataSchemas.create</code></li>
<li><code>visionai.dataSchemas.delete</code></li>
<li><code>visionai.dataSchemas.get</code></li>
<li><code>visionai.dataSchemas.list</code></li>
<li><code>visionai.dataSchemas.update</code></li>
<li><code>visionai.dataSchemas.validate</code></li>
<li><code>visionai.drafts.create</code></li>
<li><code>visionai.drafts.delete</code></li>
<li><code>visionai.drafts.get</code></li>
<li><code>visionai.drafts.list</code></li>
<li><code>visionai.drafts.update</code></li>
<li><code>visionai.events.create</code></li>
<li><code>visionai.events.delete</code></li>
<li><code>visionai.events.get</code></li>
<li><code>visionai.events.getIamPolicy</code></li>
<li><code>visionai.events.list</code></li>
<li><code>visionai.events.setIamPolicy</code></li>
<li><code>visionai.events.update</code></li>
<li><code>visionai.indexEndpoints.create</code></li>
<li><code>visionai.indexEndpoints.delete</code></li>
<li><code>visionai.indexEndpoints.deploy</code></li>
<li><code>visionai.indexEndpoints.get</code></li>
<li><code>visionai.indexEndpoints.list</code></li>
<li><code>visionai.indexEndpoints.search</code></li>
<li><code>visionai. indexEndpoints. undeploy</code></li>
<li><code>visionai.indexEndpoints.update</code></li>
<li><code>visionai.indexes.create</code></li>
<li><code>visionai.indexes.delete</code></li>
<li><code>visionai.indexes.get</code></li>
<li><code>visionai.indexes.list</code></li>
<li><code>visionai.indexes.update</code></li>
<li><code>visionai.indexes.viewAssets</code></li>
<li><code>visionai.instances.get</code></li>
<li><code>visionai.instances.list</code></li>
<li><code>visionai.locations.get</code></li>
<li><code>visionai.locations.list</code></li>
<li><code>visionai.operations.cancel</code></li>
<li><code>visionai.operations.delete</code></li>
<li><code>visionai.operations.get</code></li>
<li><code>visionai.operations.list</code></li>
<li><code>visionai.operations.wait</code></li>
<li><code>visionai.operators.create</code></li>
<li><code>visionai.operators.delete</code></li>
<li><code>visionai.operators.get</code></li>
<li><code>visionai. operators. getIamPolicy</code></li>
<li><code>visionai.operators.list</code></li>
<li><code>visionai. operators. setIamPolicy</code></li>
<li><code>visionai.operators.update</code></li>
<li><code>visionai.processors.create</code></li>
<li><code>visionai.processors.delete</code></li>
<li><code>visionai.processors.get</code></li>
<li><code>visionai.processors.list</code></li>
<li><code>visionai. processors. listPrebuilt</code></li>
<li><code>visionai.processors.update</code></li>
<li><code>visionai.searchConfigs.create</code></li>
<li><code>visionai.searchConfigs.delete</code></li>
<li><code>visionai.searchConfigs.get</code></li>
<li><code>visionai.searchConfigs.list</code></li>
<li><code>visionai.searchConfigs.update</code></li>
<li><code>visionai.series.acquireLease</code></li>
<li><code>visionai.series.create</code></li>
<li><code>visionai.series.delete</code></li>
<li><code>visionai.series.get</code></li>
<li><code>visionai.series.getIamPolicy</code></li>
<li><code>visionai.series.list</code></li>
<li><code>visionai.series.receive</code></li>
<li><code>visionai.series.releaseLease</code></li>
<li><code>visionai.series.renewLease</code></li>
<li><code>visionai.series.send</code></li>
<li><code>visionai.series.setIamPolicy</code></li>
<li><code>visionai.series.update</code></li>
<li><code>visionai.streams.create</code></li>
<li><code>visionai.streams.delete</code></li>
<li><code>visionai.streams.get</code></li>
<li><code>visionai.streams.getIamPolicy</code></li>
<li><code>visionai.streams.list</code></li>
<li><code>visionai.streams.receive</code></li>
<li><code>visionai.streams.send</code></li>
<li><code>visionai.streams.setIamPolicy</code></li>
<li><code>visionai.streams.update</code></li>
<li><code>visionai.uistreams.create</code></li>
<li><code>visionai.uistreams.delete</code></li>
<li><code>visionai. uistreams. generateStreamThumbnails</code></li>
<li><code>visionai.uistreams.get</code></li>
<li><code>visionai.uistreams.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>VisionAI Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.editor</code> )</p>
<p>Edit access to Vision AI all resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>visionai.analyses.create</code></p>
<p><code>visionai.analyses.delete</code></p>
<p><code>visionai.analyses.get</code></p>
<p><code>visionai.analyses.getIamPolicy</code></p>
<p><code>visionai.analyses.list</code></p>
<p><code>visionai.analyses.update</code></p>
<p><code>visionai.annotations.*</code></p>
<ul>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
</ul>
<p><code>visionai.applications.*</code></p>
<ul>
<li><code>visionai.applications.create</code></li>
<li><code>visionai.applications.delete</code></li>
<li><code>visionai.applications.deploy</code></li>
<li><code>visionai.applications.get</code></li>
<li><code>visionai.applications.list</code></li>
<li><code>visionai.applications.undeploy</code></li>
<li><code>visionai.applications.update</code></li>
</ul>
<p><code>visionai.assets.*</code></p>
<ul>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
</ul>
<p><code>visionai.clusters.create</code></p>
<p><code>visionai.clusters.delete</code></p>
<p><code>visionai.clusters.get</code></p>
<p><code>visionai.clusters.getIamPolicy</code></p>
<p><code>visionai.clusters.list</code></p>
<p><code>visionai.clusters.update</code></p>
<p><code>visionai.clusters.watch</code></p>
<p><code>visionai.corpora.*</code></p>
<ul>
<li><code>visionai.corpora.analyze</code></li>
<li><code>visionai.corpora.create</code></li>
<li><code>visionai.corpora.delete</code></li>
<li><code>visionai.corpora.get</code></li>
<li><code>visionai.corpora.import</code></li>
<li><code>visionai.corpora.list</code></li>
<li><code>visionai.corpora.suggest</code></li>
<li><code>visionai.corpora.update</code></li>
</ul>
<p><code>visionai.dataSchemas.*</code></p>
<ul>
<li><code>visionai.dataSchemas.create</code></li>
<li><code>visionai.dataSchemas.delete</code></li>
<li><code>visionai.dataSchemas.get</code></li>
<li><code>visionai.dataSchemas.list</code></li>
<li><code>visionai.dataSchemas.update</code></li>
<li><code>visionai.dataSchemas.validate</code></li>
</ul>
<p><code>visionai.drafts.*</code></p>
<ul>
<li><code>visionai.drafts.create</code></li>
<li><code>visionai.drafts.delete</code></li>
<li><code>visionai.drafts.get</code></li>
<li><code>visionai.drafts.list</code></li>
<li><code>visionai.drafts.update</code></li>
</ul>
<p><code>visionai.events.create</code></p>
<p><code>visionai.events.delete</code></p>
<p><code>visionai.events.get</code></p>
<p><code>visionai.events.getIamPolicy</code></p>
<p><code>visionai.events.list</code></p>
<p><code>visionai.events.update</code></p>
<p><code>visionai.indexEndpoints.*</code></p>
<ul>
<li><code>visionai.indexEndpoints.create</code></li>
<li><code>visionai.indexEndpoints.delete</code></li>
<li><code>visionai.indexEndpoints.deploy</code></li>
<li><code>visionai.indexEndpoints.get</code></li>
<li><code>visionai.indexEndpoints.list</code></li>
<li><code>visionai.indexEndpoints.search</code></li>
<li><code>visionai. indexEndpoints. undeploy</code></li>
<li><code>visionai.indexEndpoints.update</code></li>
</ul>
<p><code>visionai.indexes.*</code></p>
<ul>
<li><code>visionai.indexes.create</code></li>
<li><code>visionai.indexes.delete</code></li>
<li><code>visionai.indexes.get</code></li>
<li><code>visionai.indexes.list</code></li>
<li><code>visionai.indexes.update</code></li>
<li><code>visionai.indexes.viewAssets</code></li>
</ul>
<p><code>visionai.instances.*</code></p>
<ul>
<li><code>visionai.instances.get</code></li>
<li><code>visionai.instances.list</code></li>
</ul>
<p><code>visionai.locations.*</code></p>
<ul>
<li><code>visionai.locations.get</code></li>
<li><code>visionai.locations.list</code></li>
</ul>
<p><code>visionai.operations.*</code></p>
<ul>
<li><code>visionai.operations.cancel</code></li>
<li><code>visionai.operations.delete</code></li>
<li><code>visionai.operations.get</code></li>
<li><code>visionai.operations.list</code></li>
<li><code>visionai.operations.wait</code></li>
</ul>
<p><code>visionai.operators.create</code></p>
<p><code>visionai.operators.delete</code></p>
<p><code>visionai.operators.get</code></p>
<p><code>visionai. operators. getIamPolicy</code></p>
<p><code>visionai.operators.list</code></p>
<p><code>visionai.operators.update</code></p>
<p><code>visionai.processors.*</code></p>
<ul>
<li><code>visionai.processors.create</code></li>
<li><code>visionai.processors.delete</code></li>
<li><code>visionai.processors.get</code></li>
<li><code>visionai.processors.list</code></li>
<li><code>visionai. processors. listPrebuilt</code></li>
<li><code>visionai.processors.update</code></li>
</ul>
<p><code>visionai.searchConfigs.*</code></p>
<ul>
<li><code>visionai.searchConfigs.create</code></li>
<li><code>visionai.searchConfigs.delete</code></li>
<li><code>visionai.searchConfigs.get</code></li>
<li><code>visionai.searchConfigs.list</code></li>
<li><code>visionai.searchConfigs.update</code></li>
</ul>
<p><code>visionai.series.acquireLease</code></p>
<p><code>visionai.series.create</code></p>
<p><code>visionai.series.delete</code></p>
<p><code>visionai.series.get</code></p>
<p><code>visionai.series.getIamPolicy</code></p>
<p><code>visionai.series.list</code></p>
<p><code>visionai.series.receive</code></p>
<p><code>visionai.series.releaseLease</code></p>
<p><code>visionai.series.renewLease</code></p>
<p><code>visionai.series.send</code></p>
<p><code>visionai.series.update</code></p>
<p><code>visionai.streams.create</code></p>
<p><code>visionai.streams.delete</code></p>
<p><code>visionai.streams.get</code></p>
<p><code>visionai.streams.getIamPolicy</code></p>
<p><code>visionai.streams.list</code></p>
<p><code>visionai.streams.receive</code></p>
<p><code>visionai.streams.send</code></p>
<p><code>visionai.streams.update</code></p>
<p><code>visionai.uistreams.*</code></p>
<ul>
<li><code>visionai.uistreams.create</code></li>
<li><code>visionai.uistreams.delete</code></li>
<li><code>visionai. uistreams. generateStreamThumbnails</code></li>
<li><code>visionai.uistreams.get</code></li>
<li><code>visionai.uistreams.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>VisionAI Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.viewer</code> )</p>
<p>View access to Vision AI all resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>visionai.analyses.get</code></p>
<p><code>visionai.analyses.getIamPolicy</code></p>
<p><code>visionai.analyses.list</code></p>
<p><code>visionai.annotations.get</code></p>
<p><code>visionai.annotations.list</code></p>
<p><code>visionai.applications.get</code></p>
<p><code>visionai.applications.list</code></p>
<p><code>visionai.assets.clip</code></p>
<p><code>visionai.assets.generateHlsUri</code></p>
<p><code>visionai.assets.get</code></p>
<p><code>visionai.assets.list</code></p>
<p><code>visionai.assets.search</code></p>
<p><code>visionai.clusters.get</code></p>
<p><code>visionai.clusters.getIamPolicy</code></p>
<p><code>visionai.clusters.list</code></p>
<p><code>visionai.corpora.get</code></p>
<p><code>visionai.corpora.list</code></p>
<p><code>visionai.corpora.suggest</code></p>
<p><code>visionai.dataSchemas.get</code></p>
<p><code>visionai.dataSchemas.list</code></p>
<p><code>visionai.dataSchemas.validate</code></p>
<p><code>visionai.drafts.get</code></p>
<p><code>visionai.drafts.list</code></p>
<p><code>visionai.events.get</code></p>
<p><code>visionai.events.getIamPolicy</code></p>
<p><code>visionai.events.list</code></p>
<p><code>visionai.indexEndpoints.get</code></p>
<p><code>visionai.indexEndpoints.list</code></p>
<p><code>visionai.indexEndpoints.search</code></p>
<p><code>visionai.indexes.get</code></p>
<p><code>visionai.indexes.list</code></p>
<p><code>visionai.indexes.viewAssets</code></p>
<p><code>visionai.instances.*</code></p>
<ul>
<li><code>visionai.instances.get</code></li>
<li><code>visionai.instances.list</code></li>
</ul>
<p><code>visionai.locations.*</code></p>
<ul>
<li><code>visionai.locations.get</code></li>
<li><code>visionai.locations.list</code></li>
</ul>
<p><code>visionai.operations.get</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai.operators.get</code></p>
<p><code>visionai. operators. getIamPolicy</code></p>
<p><code>visionai.operators.list</code></p>
<p><code>visionai.processors.get</code></p>
<p><code>visionai.processors.list</code></p>
<p><code>visionai. processors. listPrebuilt</code></p>
<p><code>visionai.searchConfigs.get</code></p>
<p><code>visionai.searchConfigs.list</code></p>
<p><code>visionai.series.get</code></p>
<p><code>visionai.series.getIamPolicy</code></p>
<p><code>visionai.series.list</code></p>
<p><code>visionai.streams.get</code></p>
<p><code>visionai.streams.getIamPolicy</code></p>
<p><code>visionai.streams.list</code></p>
<p><code>visionai.uistreams.get</code></p>
<p><code>visionai.uistreams.list</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Analysis Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.analysisEditor</code> )</p>
<p>Access to read and write Vision AI Analyses.</p></td>
<td><p><code>visionai.analyses.create</code></p>
<p><code>visionai.analyses.delete</code></p>
<p><code>visionai.analyses.get</code></p>
<p><code>visionai.analyses.list</code></p>
<p><code>visionai.analyses.update</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Analysis Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.analysisViewer</code> )</p>
<p>Access to read Vision AI Analyses.</p></td>
<td><p><code>visionai.analyses.get</code></p>
<p><code>visionai.analyses.list</code></p></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse Annotation Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.annotationEditor</code> )</p>
<p>Grants access to edit media asset annotations into the Warehouse.</p></td>
<td><p><code>visionai.annotations.*</code></p>
<ul>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>VisionAI Warehouse Annotation Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.annotationViewer</code> )</p>
<p>Grants access to view media asset annotations into the Warehouse.</p></td>
<td><p><code>visionai.annotations.get</code></p>
<p><code>visionai.annotations.list</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Application Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Access to read and write Vision AI Applications.</p></td>
<td><p><code>visionai.applications.*</code></p>
<ul>
<li><code>visionai.applications.create</code></li>
<li><code>visionai.applications.delete</code></li>
<li><code>visionai.applications.deploy</code></li>
<li><code>visionai.applications.get</code></li>
<li><code>visionai.applications.list</code></li>
<li><code>visionai.applications.undeploy</code></li>
<li><code>visionai.applications.update</code></li>
</ul>
<p><code>visionai.drafts.*</code></p>
<ul>
<li><code>visionai.drafts.create</code></li>
<li><code>visionai.drafts.delete</code></li>
<li><code>visionai.drafts.get</code></li>
<li><code>visionai.drafts.list</code></li>
<li><code>visionai.drafts.update</code></li>
</ul>
<p><code>visionai.instances.*</code></p>
<ul>
<li><code>visionai.instances.get</code></li>
<li><code>visionai.instances.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Vision AI Application Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Access to read Vision AI Applications.</p></td>
<td><p><code>visionai.applications.get</code></p>
<p><code>visionai.applications.list</code></p>
<p><code>visionai.drafts.get</code></p>
<p><code>visionai.drafts.list</code></p>
<p><code>visionai.instances.*</code></p>
<ul>
<li><code>visionai.instances.get</code></li>
<li><code>visionai.instances.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse Asset Creator <sup>Beta</sup>
<p>( <code>roles/ visionai.assetCreator</code> )</p>
<p>Grants access to ingest media assets into the Warehouse.</p></td>
<td><p><code>visionai.assets.create</code></p>
<p><code>visionai.assets.ingest</code></p></td>
</tr>
<tr class="odd">
<td>VisionAI Warehouse Asset Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.assetEditor</code> )</p>
<p>Grants access to edit media assets into the Warehouse.</p></td>
<td><p><code>visionai.assets.*</code></p>
<ul>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
</ul></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse Asset Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.assetViewer</code> )</p>
<p>Grants access to view media assets into the Warehouse.</p></td>
<td><p><code>visionai.assets.get</code></p>
<p><code>visionai.assets.list</code></p>
<p><code>visionai.assets.search</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Cluster Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.clusterEditor</code> )</p>
<p>Access to read and write Vision AI Cluster.</p></td>
<td><p><code>visionai.clusters.create</code></p>
<p><code>visionai.clusters.delete</code></p>
<p><code>visionai.clusters.get</code></p>
<p><code>visionai.clusters.list</code></p>
<p><code>visionai.clusters.update</code></p>
<p><code>visionai.clusters.watch</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Cluster Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.clusterViewer</code> )</p>
<p>Access to read Vision AI Clusters.</p></td>
<td><p><code>visionai.clusters.get</code></p>
<p><code>visionai.clusters.list</code></p></td>
</tr>
<tr class="odd">
<td>VisionAI Warehouse Corpus Administrator <sup>Beta</sup>
<p>( <code>roles/ visionai.corpusAdmin</code> )</p>
<p>Full control to everything in a corpus including corpus access control.</p></td>
<td><p><code>visionai.annotations.*</code></p>
<ul>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
</ul>
<p><code>visionai.assets.*</code></p>
<ul>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
</ul>
<p><code>visionai.corpora.*</code></p>
<ul>
<li><code>visionai.corpora.analyze</code></li>
<li><code>visionai.corpora.create</code></li>
<li><code>visionai.corpora.delete</code></li>
<li><code>visionai.corpora.get</code></li>
<li><code>visionai.corpora.import</code></li>
<li><code>visionai.corpora.list</code></li>
<li><code>visionai.corpora.suggest</code></li>
<li><code>visionai.corpora.update</code></li>
</ul>
<p><code>visionai.dataSchemas.*</code></p>
<ul>
<li><code>visionai.dataSchemas.create</code></li>
<li><code>visionai.dataSchemas.delete</code></li>
<li><code>visionai.dataSchemas.get</code></li>
<li><code>visionai.dataSchemas.list</code></li>
<li><code>visionai.dataSchemas.update</code></li>
<li><code>visionai.dataSchemas.validate</code></li>
</ul>
<p><code>visionai.indexes.*</code></p>
<ul>
<li><code>visionai.indexes.create</code></li>
<li><code>visionai.indexes.delete</code></li>
<li><code>visionai.indexes.get</code></li>
<li><code>visionai.indexes.list</code></li>
<li><code>visionai.indexes.update</code></li>
<li><code>visionai.indexes.viewAssets</code></li>
</ul>
<p><code>visionai.operations.get</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai.searchConfigs.*</code></p>
<ul>
<li><code>visionai.searchConfigs.create</code></li>
<li><code>visionai.searchConfigs.delete</code></li>
<li><code>visionai.searchConfigs.get</code></li>
<li><code>visionai.searchConfigs.list</code></li>
<li><code>visionai.searchConfigs.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse Corpus Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.corpusEditor</code> )</p>
<p>Read-write access to everything in a corpus.</p></td>
<td><p><code>visionai.annotations.*</code></p>
<ul>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
</ul>
<p><code>visionai.assets.*</code></p>
<ul>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
</ul>
<p><code>visionai.corpora.*</code></p>
<ul>
<li><code>visionai.corpora.analyze</code></li>
<li><code>visionai.corpora.create</code></li>
<li><code>visionai.corpora.delete</code></li>
<li><code>visionai.corpora.get</code></li>
<li><code>visionai.corpora.import</code></li>
<li><code>visionai.corpora.list</code></li>
<li><code>visionai.corpora.suggest</code></li>
<li><code>visionai.corpora.update</code></li>
</ul>
<p><code>visionai.dataSchemas.*</code></p>
<ul>
<li><code>visionai.dataSchemas.create</code></li>
<li><code>visionai.dataSchemas.delete</code></li>
<li><code>visionai.dataSchemas.get</code></li>
<li><code>visionai.dataSchemas.list</code></li>
<li><code>visionai.dataSchemas.update</code></li>
<li><code>visionai.dataSchemas.validate</code></li>
</ul>
<p><code>visionai.indexes.*</code></p>
<ul>
<li><code>visionai.indexes.create</code></li>
<li><code>visionai.indexes.delete</code></li>
<li><code>visionai.indexes.get</code></li>
<li><code>visionai.indexes.list</code></li>
<li><code>visionai.indexes.update</code></li>
<li><code>visionai.indexes.viewAssets</code></li>
</ul>
<p><code>visionai.operations.get</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai.searchConfigs.*</code></p>
<ul>
<li><code>visionai.searchConfigs.create</code></li>
<li><code>visionai.searchConfigs.delete</code></li>
<li><code>visionai.searchConfigs.get</code></li>
<li><code>visionai.searchConfigs.list</code></li>
<li><code>visionai.searchConfigs.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>VisionAI Warehouse Corpus Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Grants access to view everything in a corpus.</p></td>
<td><p><code>visionai.annotations.get</code></p>
<p><code>visionai.annotations.list</code></p>
<p><code>visionai.assets.clip</code></p>
<p><code>visionai.assets.generateHlsUri</code></p>
<p><code>visionai.assets.get</code></p>
<p><code>visionai.assets.list</code></p>
<p><code>visionai.assets.search</code></p>
<p><code>visionai.corpora.get</code></p>
<p><code>visionai.corpora.list</code></p>
<p><code>visionai.corpora.suggest</code></p>
<p><code>visionai.dataSchemas.get</code></p>
<p><code>visionai.dataSchemas.list</code></p>
<p><code>visionai.dataSchemas.validate</code></p>
<p><code>visionai.indexes.get</code></p>
<p><code>visionai.indexes.list</code></p>
<p><code>visionai.indexes.viewAssets</code></p>
<p><code>visionai.operations.get</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai.searchConfigs.get</code></p>
<p><code>visionai.searchConfigs.list</code></p></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse Corpus Writer <sup>Beta</sup>
<p>( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Grants access to create/update/delete everything in a corpus.</p></td>
<td><p><code>visionai.annotations.*</code></p>
<ul>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
</ul>
<p><code>visionai.assets.*</code></p>
<ul>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
</ul>
<p><code>visionai.corpora.analyze</code></p>
<p><code>visionai.corpora.delete</code></p>
<p><code>visionai.corpora.import</code></p>
<p><code>visionai.corpora.update</code></p>
<p><code>visionai.dataSchemas.create</code></p>
<p><code>visionai.dataSchemas.delete</code></p>
<p><code>visionai.dataSchemas.update</code></p>
<p><code>visionai.indexes.create</code></p>
<p><code>visionai.indexes.delete</code></p>
<p><code>visionai.indexes.update</code></p>
<p><code>visionai.operations.get</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai.searchConfigs.create</code></p>
<p><code>visionai.searchConfigs.delete</code></p>
<p><code>visionai.searchConfigs.update</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Event Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.eventEditor</code> )</p>
<p>Access to read and write Vision AI Events.</p></td>
<td><p><code>visionai.events.create</code></p>
<p><code>visionai.events.delete</code></p>
<p><code>visionai.events.get</code></p>
<p><code>visionai.events.list</code></p>
<p><code>visionai.events.update</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Event Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.eventViewer</code> )</p>
<p>Access to read Vision AI Events.</p></td>
<td><p><code>visionai.events.get</code></p>
<p><code>visionai.events.list</code></p></td>
</tr>
<tr class="odd">
<td>VisionAI Warehouse IndexEndpoint Administrator <sup>Beta</sup>
<p>( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p>Full control of all Media Warehouse resources and permissions.</p></td>
<td><p><code>visionai.indexEndpoints.*</code></p>
<ul>
<li><code>visionai.indexEndpoints.create</code></li>
<li><code>visionai.indexEndpoints.delete</code></li>
<li><code>visionai.indexEndpoints.deploy</code></li>
<li><code>visionai.indexEndpoints.get</code></li>
<li><code>visionai.indexEndpoints.list</code></li>
<li><code>visionai.indexEndpoints.search</code></li>
<li><code>visionai. indexEndpoints. undeploy</code></li>
<li><code>visionai.indexEndpoints.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse IndexEndpoint Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p>Read, write and create access to all index endpoints level resources.</p></td>
<td><p><code>visionai.indexEndpoints.*</code></p>
<ul>
<li><code>visionai.indexEndpoints.create</code></li>
<li><code>visionai.indexEndpoints.delete</code></li>
<li><code>visionai.indexEndpoints.deploy</code></li>
<li><code>visionai.indexEndpoints.get</code></li>
<li><code>visionai.indexEndpoints.list</code></li>
<li><code>visionai.indexEndpoints.search</code></li>
<li><code>visionai. indexEndpoints. undeploy</code></li>
<li><code>visionai.indexEndpoints.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>VisionAI Warehouse IndexEndpoint Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.indexEndpointViewer</code> )</p>
<p>Grants access to view all index endpoint resources and be able to search on them. (ReadOnly)</p></td>
<td><p><code>visionai.indexEndpoints.get</code></p>
<p><code>visionai.indexEndpoints.list</code></p>
<p><code>visionai.indexEndpoints.search</code></p></td>
</tr>
<tr class="even">
<td>VisionAI Warehouse IndexEndpoint Writer <sup>Beta</sup>
<p>( <code>roles/ visionai.indexEndpointWriter</code> )</p>
<p>Grants access to perform update, delete, deploy and undeploy operations on the index endpoint.</p></td>
<td><p><code>visionai.indexEndpoints.delete</code></p>
<p><code>visionai.indexEndpoints.deploy</code></p>
<p><code>visionai. indexEndpoints. undeploy</code></p>
<p><code>visionai.indexEndpoints.update</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Operator Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.operatorEditor</code> )</p>
<p>Access to read and write Vision AI Operators.</p></td>
<td><p><code>visionai.operators.create</code></p>
<p><code>visionai.operators.delete</code></p>
<p><code>visionai.operators.get</code></p>
<p><code>visionai.operators.list</code></p>
<p><code>visionai.operators.update</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Operator Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.operatorViewer</code> )</p>
<p>Access to read Vision AI Operators.</p></td>
<td><p><code>visionai.operators.get</code></p>
<p><code>visionai.operators.list</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Packet Receiver <sup>Beta</sup>
<p>( <code>roles/ visionai.packetReceiver</code> )</p>
<p>Access to read Vision AI Series.</p></td>
<td><p><code>visionai.clusters.watch</code></p>
<p><code>visionai.series.acquireLease</code></p>
<p><code>visionai.series.receive</code></p>
<p><code>visionai.series.releaseLease</code></p>
<p><code>visionai.series.renewLease</code></p>
<p><code>visionai.streams.receive</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Packet Sender <sup>Beta</sup>
<p>( <code>roles/ visionai.packetSender</code> )</p>
<p>Packet sender to the series.</p></td>
<td><p><code>visionai.series.acquireLease</code></p>
<p><code>visionai.series.releaseLease</code></p>
<p><code>visionai.series.renewLease</code></p>
<p><code>visionai.series.send</code></p>
<p><code>visionai.streams.send</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Processor Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.processorEditor</code> )</p>
<p>Access to read and write Vision AI Processors.</p></td>
<td><p><code>visionai.processors.*</code></p>
<ul>
<li><code>visionai.processors.create</code></li>
<li><code>visionai.processors.delete</code></li>
<li><code>visionai.processors.get</code></li>
<li><code>visionai.processors.list</code></li>
<li><code>visionai. processors. listPrebuilt</code></li>
<li><code>visionai.processors.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Vision AI Processor Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.processorViewer</code> )</p>
<p>Access to read Vision AI Processors.</p></td>
<td><p><code>visionai.processors.get</code></p>
<p><code>visionai.processors.list</code></p>
<p><code>visionai. processors. listPrebuilt</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI RetailCatalog Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.retailcatalogEditor</code> )</p>
<p>Access to read and write Vision AI RetailCatalogs.</p></td>
<td></td>
</tr>
<tr class="even">
<td>Vision AI RetailCatalog Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.retailcatalogViewer</code> )</p>
<p>Access to read Vision AI RetailCatalogs.</p></td>
<td></td>
</tr>
<tr class="odd">
<td>Vision AI RetailEndpoint Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.retailendpointEditor</code> )</p>
<p>Access to read and write Vision AI RetailEndpoints.</p></td>
<td></td>
</tr>
<tr class="even">
<td>Vision AI RetailEndpoint Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.retailendpointViewer</code> )</p>
<p>Access to read Vision AI RetailEndpoints.</p></td>
<td></td>
</tr>
<tr class="odd">
<td>Vision AI Series Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.seriesEditor</code> )</p>
<p>Access to read and write Vision AI Series.</p></td>
<td><p><code>visionai.clusters.watch</code></p>
<p><code>visionai.series.acquireLease</code></p>
<p><code>visionai.series.create</code></p>
<p><code>visionai.series.delete</code></p>
<p><code>visionai.series.get</code></p>
<p><code>visionai.series.list</code></p>
<p><code>visionai.series.receive</code></p>
<p><code>visionai.series.releaseLease</code></p>
<p><code>visionai.series.renewLease</code></p>
<p><code>visionai.series.send</code></p>
<p><code>visionai.series.update</code></p>
<p><code>visionai.streams.receive</code></p>
<p><code>visionai.streams.send</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Series Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.seriesViewer</code> )</p>
<p>Access to read Vision AI Series.</p></td>
<td><p><code>visionai.series.get</code></p>
<p><code>visionai.series.list</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI Stream Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.streamEditor</code> )</p>
<p>Access to read and write Vision AI Streams.</p></td>
<td><p><code>visionai.clusters.watch</code></p>
<p><code>visionai.series.acquireLease</code></p>
<p><code>visionai.series.receive</code></p>
<p><code>visionai.series.releaseLease</code></p>
<p><code>visionai.series.renewLease</code></p>
<p><code>visionai.series.send</code></p>
<p><code>visionai.streams.create</code></p>
<p><code>visionai.streams.delete</code></p>
<p><code>visionai.streams.get</code></p>
<p><code>visionai.streams.list</code></p>
<p><code>visionai.streams.receive</code></p>
<p><code>visionai.streams.send</code></p>
<p><code>visionai.streams.update</code></p></td>
</tr>
<tr class="even">
<td>Vision AI Stream Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.streamViewer</code> )</p>
<p>Access to read Vision AI Streams.</p></td>
<td><p><code>visionai.streams.get</code></p>
<p><code>visionai.streams.list</code></p></td>
</tr>
<tr class="odd">
<td>Vision AI UI Stream Editor <sup>Beta</sup>
<p>( <code>roles/ visionai.uiStreamEditor</code> )</p>
<p>Access to read &amp; write Vision AI UI Streams.</p></td>
<td><p><code>visionai.uistreams.*</code></p>
<ul>
<li><code>visionai.uistreams.create</code></li>
<li><code>visionai.uistreams.delete</code></li>
<li><code>visionai. uistreams. generateStreamThumbnails</code></li>
<li><code>visionai.uistreams.get</code></li>
<li><code>visionai.uistreams.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Vision AI UI Stream Viewer <sup>Beta</sup>
<p>( <code>roles/ visionai.uiStreamViewer</code> )</p>
<p>Access to read Vision AI UI Streams.</p></td>
<td><p><code>visionai.uistreams.get</code></p>
<p><code>visionai.uistreams.list</code></p></td>
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
<td>Cloud Vision AI Service Agent
<p>( <code>roles/ visionai.serviceAgent</code> )</p>
<p>Grants Cloud Vision AI service account permissions to manage resources in consumer project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.predict</code></p>
<p><code>aiplatform.models.export</code></p>
<p><code>aiplatform.models.get</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.models.export</code></p>
<p><code>bigquery.readsessions.create</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.export</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>bigtable.tables.get</code></p>
<p><code>bigtable.tables.list</code></p>
<p><code>bigtable.tables.readRows</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. invoke</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>compute.machineTypes.get</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>run.jobs.run</code></p>
<p><code>run.routes.invoke</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p>
<p><code>visionai.analyses.create</code></p>
<p><code>visionai.analyses.delete</code></p>
<p><code>visionai.analyses.get</code></p>
<p><code>visionai.analyses.list</code></p>
<p><code>visionai.analyses.update</code></p>
<p><code>visionai.annotations.*</code></p>
<ul>
<li><code>visionai.annotations.create</code></li>
<li><code>visionai.annotations.delete</code></li>
<li><code>visionai.annotations.get</code></li>
<li><code>visionai.annotations.list</code></li>
<li><code>visionai.annotations.update</code></li>
</ul>
<p><code>visionai.applications.*</code></p>
<ul>
<li><code>visionai.applications.create</code></li>
<li><code>visionai.applications.delete</code></li>
<li><code>visionai.applications.deploy</code></li>
<li><code>visionai.applications.get</code></li>
<li><code>visionai.applications.list</code></li>
<li><code>visionai.applications.undeploy</code></li>
<li><code>visionai.applications.update</code></li>
</ul>
<p><code>visionai.assets.*</code></p>
<ul>
<li><code>visionai.assets.analyze</code></li>
<li><code>visionai.assets.clip</code></li>
<li><code>visionai.assets.create</code></li>
<li><code>visionai.assets.delete</code></li>
<li><code>visionai.assets.generateHlsUri</code></li>
<li><code>visionai.assets.get</code></li>
<li><code>visionai.assets.index</code></li>
<li><code>visionai.assets.ingest</code></li>
<li><code>visionai.assets.list</code></li>
<li><code>visionai.assets.removeIndex</code></li>
<li><code>visionai.assets.search</code></li>
<li><code>visionai.assets.update</code></li>
<li><code>visionai.assets.upload</code></li>
</ul>
<p><code>visionai.clusters.create</code></p>
<p><code>visionai.clusters.delete</code></p>
<p><code>visionai.clusters.get</code></p>
<p><code>visionai.clusters.list</code></p>
<p><code>visionai.clusters.update</code></p>
<p><code>visionai.clusters.watch</code></p>
<p><code>visionai.corpora.*</code></p>
<ul>
<li><code>visionai.corpora.analyze</code></li>
<li><code>visionai.corpora.create</code></li>
<li><code>visionai.corpora.delete</code></li>
<li><code>visionai.corpora.get</code></li>
<li><code>visionai.corpora.import</code></li>
<li><code>visionai.corpora.list</code></li>
<li><code>visionai.corpora.suggest</code></li>
<li><code>visionai.corpora.update</code></li>
</ul>
<p><code>visionai.dataSchemas.*</code></p>
<ul>
<li><code>visionai.dataSchemas.create</code></li>
<li><code>visionai.dataSchemas.delete</code></li>
<li><code>visionai.dataSchemas.get</code></li>
<li><code>visionai.dataSchemas.list</code></li>
<li><code>visionai.dataSchemas.update</code></li>
<li><code>visionai.dataSchemas.validate</code></li>
</ul>
<p><code>visionai.drafts.*</code></p>
<ul>
<li><code>visionai.drafts.create</code></li>
<li><code>visionai.drafts.delete</code></li>
<li><code>visionai.drafts.get</code></li>
<li><code>visionai.drafts.list</code></li>
<li><code>visionai.drafts.update</code></li>
</ul>
<p><code>visionai.events.create</code></p>
<p><code>visionai.events.delete</code></p>
<p><code>visionai.events.get</code></p>
<p><code>visionai.events.list</code></p>
<p><code>visionai.events.update</code></p>
<p><code>visionai.indexEndpoints.*</code></p>
<ul>
<li><code>visionai.indexEndpoints.create</code></li>
<li><code>visionai.indexEndpoints.delete</code></li>
<li><code>visionai.indexEndpoints.deploy</code></li>
<li><code>visionai.indexEndpoints.get</code></li>
<li><code>visionai.indexEndpoints.list</code></li>
<li><code>visionai.indexEndpoints.search</code></li>
<li><code>visionai. indexEndpoints. undeploy</code></li>
<li><code>visionai.indexEndpoints.update</code></li>
</ul>
<p><code>visionai.indexes.*</code></p>
<ul>
<li><code>visionai.indexes.create</code></li>
<li><code>visionai.indexes.delete</code></li>
<li><code>visionai.indexes.get</code></li>
<li><code>visionai.indexes.list</code></li>
<li><code>visionai.indexes.update</code></li>
<li><code>visionai.indexes.viewAssets</code></li>
</ul>
<p><code>visionai.instances.*</code></p>
<ul>
<li><code>visionai.instances.get</code></li>
<li><code>visionai.instances.list</code></li>
</ul>
<p><code>visionai.operations.get</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai.operators.create</code></p>
<p><code>visionai.operators.delete</code></p>
<p><code>visionai.operators.get</code></p>
<p><code>visionai.operators.list</code></p>
<p><code>visionai.operators.update</code></p>
<p><code>visionai.processors.create</code></p>
<p><code>visionai.processors.delete</code></p>
<p><code>visionai.processors.get</code></p>
<p><code>visionai.processors.list</code></p>
<p><code>visionai.processors.update</code></p>
<p><code>visionai.searchConfigs.*</code></p>
<ul>
<li><code>visionai.searchConfigs.create</code></li>
<li><code>visionai.searchConfigs.delete</code></li>
<li><code>visionai.searchConfigs.get</code></li>
<li><code>visionai.searchConfigs.list</code></li>
<li><code>visionai.searchConfigs.update</code></li>
</ul>
<p><code>visionai.series.acquireLease</code></p>
<p><code>visionai.series.create</code></p>
<p><code>visionai.series.delete</code></p>
<p><code>visionai.series.get</code></p>
<p><code>visionai.series.list</code></p>
<p><code>visionai.series.receive</code></p>
<p><code>visionai.series.releaseLease</code></p>
<p><code>visionai.series.renewLease</code></p>
<p><code>visionai.series.send</code></p>
<p><code>visionai.series.update</code></p>
<p><code>visionai.streams.create</code></p>
<p><code>visionai.streams.delete</code></p>
<p><code>visionai.streams.get</code></p>
<p><code>visionai.streams.list</code></p>
<p><code>visionai.streams.receive</code></p>
<p><code>visionai.streams.send</code></p>
<p><code>visionai.streams.update</code></p>
<p><code>visionai.uistreams.*</code></p>
<ul>
<li><code>visionai.uistreams.create</code></li>
<li><code>visionai.uistreams.delete</code></li>
<li><code>visionai. uistreams. generateStreamThumbnails</code></li>
<li><code>visionai.uistreams.get</code></li>
<li><code>visionai.uistreams.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Vision AI permissions

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
<td><code>visionai.analyses.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code>roles/ visionai.analysisEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.analyses.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code>roles/ visionai.analysisEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.analyses.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code>roles/ visionai.analysisEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisViewer">Vision AI Analysis Viewer</a> ( <code>roles/ visionai.analysisViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.analyses.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.analyses.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code>roles/ visionai.analysisEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisViewer">Vision AI Analysis Viewer</a> ( <code>roles/ visionai.analysisViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.analyses.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.analyses.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code>roles/ visionai.analysisEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.annotations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code>roles/ visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.annotations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code>roles/ visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.annotations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code>roles/ visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationViewer">VisionAI Warehouse Annotation Viewer</a> ( <code>roles/ visionai.annotationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.annotations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code>roles/ visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationViewer">VisionAI Warehouse Annotation Viewer</a> ( <code>roles/ visionai.annotationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.annotations.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code>roles/ visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.applications.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.applications.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.applications.deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.applications.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.applications.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.applications.undeploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.applications.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.analyze</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.assets.clip</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetCreator">VisionAI Warehouse Asset Creator</a> ( <code>roles/ visionai.assetCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.assets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.generateHlsUri</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.assets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetViewer">VisionAI Warehouse Asset Viewer</a> ( <code>roles/ visionai.assetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.index</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.assets.ingest</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetCreator">VisionAI Warehouse Asset Creator</a> ( <code>roles/ visionai.assetCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetViewer">VisionAI Warehouse Asset Viewer</a> ( <code>roles/ visionai.assetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.assets.removeIndex</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetViewer">VisionAI Warehouse Asset Viewer</a> ( <code>roles/ visionai.assetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.assets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.assets.upload</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code>roles/ visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.clusters.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code>roles/ visionai.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.clusters.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code>roles/ visionai.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.clusters.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code>roles/ visionai.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterViewer">Vision AI Cluster Viewer</a> ( <code>roles/ visionai.clusterViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.clusters.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.clusters.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code>roles/ visionai.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterViewer">Vision AI Cluster Viewer</a> ( <code>roles/ visionai.clusterViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.clusters.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.clusters.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code>roles/ visionai.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.clusters.watch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code>roles/ visionai.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code>roles/ visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.corpora.analyze</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.corpora.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.corpora.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.corpora.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.corpora.import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.corpora.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.corpora.suggest</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.corpora.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.dataSchemas.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.dataSchemas.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.dataSchemas.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.dataSchemas.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.dataSchemas.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.dataSchemas.validate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.drafts.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.drafts.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.drafts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.drafts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.drafts.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.events.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code>roles/ visionai.eventEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.events.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code>roles/ visionai.eventEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.events.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code>roles/ visionai.eventEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventViewer">Vision AI Event Viewer</a> ( <code>roles/ visionai.eventViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.events.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.events.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code>roles/ visionai.eventEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventViewer">Vision AI Event Viewer</a> ( <code>roles/ visionai.eventViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.events.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.events.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code>roles/ visionai.eventEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.indexEndpoints.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexEndpoints.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code>roles/ visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.indexEndpoints.deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code>roles/ visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexEndpoints.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointViewer">VisionAI Warehouse IndexEndpoint Viewer</a> ( <code>roles/ visionai.indexEndpointViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.indexEndpoints.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointViewer">VisionAI Warehouse IndexEndpoint Viewer</a> ( <code>roles/ visionai.indexEndpointViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexEndpoints.search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointViewer">VisionAI Warehouse IndexEndpoint Viewer</a> ( <code>roles/ visionai.indexEndpointViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai. indexEndpoints. undeploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code>roles/ visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexEndpoints.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code>roles/ visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code>roles/ visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code>roles/ visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.indexes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.indexes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.indexes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.indexes.viewAssets</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.instances.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.instances.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code>roles/ visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code>roles/ visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.operations.wait</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.operators.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code>roles/ visionai.operatorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.operators.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code>roles/ visionai.operatorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.operators.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code>roles/ visionai.operatorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorViewer">Vision AI Operator Viewer</a> ( <code>roles/ visionai.operatorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai. operators. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.operators.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code>roles/ visionai.operatorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorViewer">Vision AI Operator Viewer</a> ( <code>roles/ visionai.operatorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai. operators. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.operators.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code>roles/ visionai.operatorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.processors.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code>roles/ visionai.processorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.processors.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code>roles/ visionai.processorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.processors.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code>roles/ visionai.processorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorViewer">Vision AI Processor Viewer</a> ( <code>roles/ visionai.processorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.processors.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code>roles/ visionai.processorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorViewer">Vision AI Processor Viewer</a> ( <code>roles/ visionai.processorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai. processors. listPrebuilt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code>roles/ visionai.processorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorViewer">Vision AI Processor Viewer</a> ( <code>roles/ visionai.processorViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.processors.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code>roles/ visionai.processorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.searchConfigs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.searchConfigs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.searchConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.searchConfigs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code>roles/ visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.searchConfigs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code>roles/ visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code>roles/ visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code>roles/ visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.series.acquireLease</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code>roles/ visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code>roles/ visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.series.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.series.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.series.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesViewer">Vision AI Series Viewer</a> ( <code>roles/ visionai.seriesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.series.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.series.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesViewer">Vision AI Series Viewer</a> ( <code>roles/ visionai.seriesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.series.receive</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code>roles/ visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.series.releaseLease</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code>roles/ visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code>roles/ visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.series.renewLease</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code>roles/ visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code>roles/ visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.series.send</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code>roles/ visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.series.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>visionai.series.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.streams.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.streams.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.streams.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamViewer">Vision AI Stream Viewer</a> ( <code>roles/ visionai.streamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.streams.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.streams.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamViewer">Vision AI Stream Viewer</a> ( <code>roles/ visionai.streamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.streams.receive</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code>roles/ visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.streams.send</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code>roles/ visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code>roles/ visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.streams.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>visionai.streams.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code>roles/ visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.uistreams.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code>roles/ visionai.uiStreamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.uistreams.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code>roles/ visionai.uiStreamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai. uistreams. generateStreamThumbnails</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code>roles/ visionai.uiStreamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>visionai.uistreams.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code>roles/ visionai.uiStreamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamViewer">Vision AI UI Stream Viewer</a> ( <code>roles/ visionai.uiStreamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>visionai.uistreams.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code>roles/ visionai.uiStreamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamViewer">Vision AI UI Stream Viewer</a> ( <code>roles/ visionai.uiStreamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
