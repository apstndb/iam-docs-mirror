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
<td><h4 id="visionai.admin" class="role-title add-link" data-text="VisionAI Admin Beta" tabindex="-1">VisionAI Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p>Full access to Vision AI all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">visionai.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.analyses.create</code></li>
<li><code dir="ltr" translate="no">visionai.analyses.delete</code></li>
<li><code dir="ltr" translate="no">visionai.analyses.get</code></li>
<li><code dir="ltr" translate="no">visionai.analyses.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.analyses.list</code></li>
<li><code dir="ltr" translate="no">visionai.analyses.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.analyses.update</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
<li><code dir="ltr" translate="no">visionai.applications.create</code></li>
<li><code dir="ltr" translate="no">visionai.applications.delete</code></li>
<li><code dir="ltr" translate="no">visionai.applications.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.get</code></li>
<li><code dir="ltr" translate="no">visionai.applications.list</code></li>
<li><code dir="ltr" translate="no">visionai.applications.undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.create</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.delete</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.get</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.list</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.update</code></li>
<li><code dir="ltr" translate="no">visionai.clusters.watch</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.create</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.delete</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.get</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.import</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.list</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.suggest</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.update</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.create</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.get</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.list</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.update</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.create</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.delete</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.get</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.list</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.update</code></li>
<li><code dir="ltr" translate="no">visionai.events.create</code></li>
<li><code dir="ltr" translate="no">visionai.events.delete</code></li>
<li><code dir="ltr" translate="no">visionai.events.get</code></li>
<li><code dir="ltr" translate="no">visionai.events.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.events.list</code></li>
<li><code dir="ltr" translate="no">visionai.events.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.events.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></li>
<li><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></li>
<li><code dir="ltr" translate="no">visionai.instances.get</code></li>
<li><code dir="ltr" translate="no">visionai.instances.list</code></li>
<li><code dir="ltr" translate="no">visionai.locations.get</code></li>
<li><code dir="ltr" translate="no">visionai.locations.list</code></li>
<li><code dir="ltr" translate="no">visionai.operations.cancel</code></li>
<li><code dir="ltr" translate="no">visionai.operations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.operations.get</code></li>
<li><code dir="ltr" translate="no">visionai.operations.list</code></li>
<li><code dir="ltr" translate="no">visionai.operations.wait</code></li>
<li><code dir="ltr" translate="no">visionai.operators.create</code></li>
<li><code dir="ltr" translate="no">visionai.operators.delete</code></li>
<li><code dir="ltr" translate="no">visionai.operators.get</code></li>
<li><code dir="ltr" translate="no">visionai.  operators.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.operators.list</code></li>
<li><code dir="ltr" translate="no">visionai.  operators.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.operators.update</code></li>
<li><code dir="ltr" translate="no">visionai.processors.create</code></li>
<li><code dir="ltr" translate="no">visionai.processors.delete</code></li>
<li><code dir="ltr" translate="no">visionai.processors.get</code></li>
<li><code dir="ltr" translate="no">visionai.processors.list</code></li>
<li><code dir="ltr" translate="no">visionai.  processors.  listPrebuilt</code></li>
<li><code dir="ltr" translate="no">visionai.processors.update</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.create</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.get</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.list</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.update</code></li>
<li><code dir="ltr" translate="no">visionai.series.acquireLease</code></li>
<li><code dir="ltr" translate="no">visionai.series.create</code></li>
<li><code dir="ltr" translate="no">visionai.series.delete</code></li>
<li><code dir="ltr" translate="no">visionai.series.get</code></li>
<li><code dir="ltr" translate="no">visionai.series.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.series.list</code></li>
<li><code dir="ltr" translate="no">visionai.series.receive</code></li>
<li><code dir="ltr" translate="no">visionai.series.releaseLease</code></li>
<li><code dir="ltr" translate="no">visionai.series.renewLease</code></li>
<li><code dir="ltr" translate="no">visionai.series.send</code></li>
<li><code dir="ltr" translate="no">visionai.series.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.series.update</code></li>
<li><code dir="ltr" translate="no">visionai.streams.create</code></li>
<li><code dir="ltr" translate="no">visionai.streams.delete</code></li>
<li><code dir="ltr" translate="no">visionai.streams.get</code></li>
<li><code dir="ltr" translate="no">visionai.streams.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.streams.list</code></li>
<li><code dir="ltr" translate="no">visionai.streams.receive</code></li>
<li><code dir="ltr" translate="no">visionai.streams.send</code></li>
<li><code dir="ltr" translate="no">visionai.streams.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">visionai.streams.update</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.create</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.delete</code></li>
<li><code dir="ltr" translate="no">visionai.  uistreams.  generateStreamThumbnails</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.get</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.editor" class="role-title add-link" data-text="VisionAI Editor Beta" tabindex="-1">VisionAI Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p>Edit access to Vision AI all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.create</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.delete</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.get</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.update</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.applications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.applications.create</code></li>
<li><code dir="ltr" translate="no">visionai.applications.delete</code></li>
<li><code dir="ltr" translate="no">visionai.applications.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.get</code></li>
<li><code dir="ltr" translate="no">visionai.applications.list</code></li>
<li><code dir="ltr" translate="no">visionai.applications.undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.clusters.create</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.delete</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.get</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.update</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.watch</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.corpora.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.create</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.delete</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.get</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.import</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.list</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.suggest</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.dataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.dataSchemas.create</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.get</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.list</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.update</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.drafts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.drafts.create</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.delete</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.get</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.list</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.events.create</code></p>
<p><code dir="ltr" translate="no">visionai.events.delete</code></p>
<p><code dir="ltr" translate="no">visionai.events.get</code></p>
<p><code dir="ltr" translate="no">visionai.events.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.update</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></li>
<li><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.indexes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexes.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.instances.get</code></li>
<li><code dir="ltr" translate="no">visionai.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.locations.get</code></li>
<li><code dir="ltr" translate="no">visionai.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.operations.cancel</code></li>
<li><code dir="ltr" translate="no">visionai.operations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.operations.get</code></li>
<li><code dir="ltr" translate="no">visionai.operations.list</code></li>
<li><code dir="ltr" translate="no">visionai.operations.wait</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.operators.create</code></p>
<p><code dir="ltr" translate="no">visionai.operators.delete</code></p>
<p><code dir="ltr" translate="no">visionai.operators.get</code></p>
<p><code dir="ltr" translate="no">visionai.  operators.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p>
<p><code dir="ltr" translate="no">visionai.operators.update</code></p>
<p><code dir="ltr" translate="no">visionai.processors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.processors.create</code></li>
<li><code dir="ltr" translate="no">visionai.processors.delete</code></li>
<li><code dir="ltr" translate="no">visionai.processors.get</code></li>
<li><code dir="ltr" translate="no">visionai.processors.list</code></li>
<li><code dir="ltr" translate="no">visionai.  processors.  listPrebuilt</code></li>
<li><code dir="ltr" translate="no">visionai.processors.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.searchConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.searchConfigs.create</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.get</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.list</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.series.acquireLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.create</code></p>
<p><code dir="ltr" translate="no">visionai.series.delete</code></p>
<p><code dir="ltr" translate="no">visionai.series.get</code></p>
<p><code dir="ltr" translate="no">visionai.series.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.receive</code></p>
<p><code dir="ltr" translate="no">visionai.series.releaseLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.renewLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.send</code></p>
<p><code dir="ltr" translate="no">visionai.series.update</code></p>
<p><code dir="ltr" translate="no">visionai.streams.create</code></p>
<p><code dir="ltr" translate="no">visionai.streams.delete</code></p>
<p><code dir="ltr" translate="no">visionai.streams.get</code></p>
<p><code dir="ltr" translate="no">visionai.streams.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p>
<p><code dir="ltr" translate="no">visionai.streams.receive</code></p>
<p><code dir="ltr" translate="no">visionai.streams.send</code></p>
<p><code dir="ltr" translate="no">visionai.streams.update</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.uistreams.create</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.delete</code></li>
<li><code dir="ltr" translate="no">visionai.  uistreams.  generateStreamThumbnails</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.get</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.viewer" class="role-title add-link" data-text="VisionAI Viewer Beta" tabindex="-1">VisionAI Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p>View access to Vision AI all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.get</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.get</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.list</code></p>
<p><code dir="ltr" translate="no">visionai.applications.get</code></p>
<p><code dir="ltr" translate="no">visionai.applications.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.clip</code></p>
<p><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></p>
<p><code dir="ltr" translate="no">visionai.assets.get</code></p>
<p><code dir="ltr" translate="no">visionai.assets.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.search</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.get</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.get</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.list</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.suggest</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.get</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.list</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></p>
<p><code dir="ltr" translate="no">visionai.drafts.get</code></p>
<p><code dir="ltr" translate="no">visionai.drafts.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.get</code></p>
<p><code dir="ltr" translate="no">visionai.events.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.get</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></p>
<p><code dir="ltr" translate="no">visionai.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.instances.get</code></li>
<li><code dir="ltr" translate="no">visionai.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.locations.get</code></li>
<li><code dir="ltr" translate="no">visionai.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.operations.get</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.operators.get</code></p>
<p><code dir="ltr" translate="no">visionai.  operators.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p>
<p><code dir="ltr" translate="no">visionai.processors.get</code></p>
<p><code dir="ltr" translate="no">visionai.processors.list</code></p>
<p><code dir="ltr" translate="no">visionai.  processors.  listPrebuilt</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.get</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.get</code></p>
<p><code dir="ltr" translate="no">visionai.series.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p>
<p><code dir="ltr" translate="no">visionai.streams.get</code></p>
<p><code dir="ltr" translate="no">visionai.streams.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.get</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.analysisEditor" class="role-title add-link" data-text="Vision AI Analysis Editor Beta" tabindex="-1">Vision AI Analysis Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.analysisEditor</code> )</p>
<p>Access to read and write Vision AI Analyses.</p></td>
<td><p><code dir="ltr" translate="no">visionai.analyses.create</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.delete</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.get</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.analysisViewer" class="role-title add-link" data-text="Vision AI Analysis Viewer Beta" tabindex="-1">Vision AI Analysis Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.analysisViewer</code> )</p>
<p>Access to read Vision AI Analyses.</p></td>
<td><p><code dir="ltr" translate="no">visionai.analyses.get</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.annotationEditor" class="role-title add-link" data-text="VisionAI Warehouse Annotation Editor Beta" tabindex="-1">VisionAI Warehouse Annotation Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.annotationEditor</code> )</p>
<p>Grants access to edit media asset annotations into the Warehouse.</p></td>
<td><p><code dir="ltr" translate="no">visionai.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.annotationViewer" class="role-title add-link" data-text="VisionAI Warehouse Annotation Viewer Beta" tabindex="-1">VisionAI Warehouse Annotation Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.annotationViewer</code> )</p>
<p>Grants access to view media asset annotations into the Warehouse.</p></td>
<td><p><code dir="ltr" translate="no">visionai.annotations.get</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.applicationEditor" class="role-title add-link" data-text="Vision AI Application Editor Beta" tabindex="-1">Vision AI Application Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Access to read and write Vision AI Applications.</p></td>
<td><p><code dir="ltr" translate="no">visionai.applications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.applications.create</code></li>
<li><code dir="ltr" translate="no">visionai.applications.delete</code></li>
<li><code dir="ltr" translate="no">visionai.applications.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.get</code></li>
<li><code dir="ltr" translate="no">visionai.applications.list</code></li>
<li><code dir="ltr" translate="no">visionai.applications.undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.drafts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.drafts.create</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.delete</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.get</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.list</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.instances.get</code></li>
<li><code dir="ltr" translate="no">visionai.instances.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.applicationViewer" class="role-title add-link" data-text="Vision AI Application Viewer Beta" tabindex="-1">Vision AI Application Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Access to read Vision AI Applications.</p></td>
<td><p><code dir="ltr" translate="no">visionai.applications.get</code></p>
<p><code dir="ltr" translate="no">visionai.applications.list</code></p>
<p><code dir="ltr" translate="no">visionai.drafts.get</code></p>
<p><code dir="ltr" translate="no">visionai.drafts.list</code></p>
<p><code dir="ltr" translate="no">visionai.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.instances.get</code></li>
<li><code dir="ltr" translate="no">visionai.instances.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assetCreator" class="role-title add-link" data-text="VisionAI Warehouse Asset Creator Beta" tabindex="-1">VisionAI Warehouse Asset Creator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.assetCreator</code> )</p>
<p>Grants access to ingest media assets into the Warehouse.</p></td>
<td><p><code dir="ltr" translate="no">visionai.assets.create</code></p>
<p><code dir="ltr" translate="no">visionai.assets.ingest</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assetEditor" class="role-title add-link" data-text="VisionAI Warehouse Asset Editor Beta" tabindex="-1">VisionAI Warehouse Asset Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p>Grants access to edit media assets into the Warehouse.</p></td>
<td><p><code dir="ltr" translate="no">visionai.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assetViewer" class="role-title add-link" data-text="VisionAI Warehouse Asset Viewer Beta" tabindex="-1">VisionAI Warehouse Asset Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.assetViewer</code> )</p>
<p>Grants access to view media assets into the Warehouse.</p></td>
<td><p><code dir="ltr" translate="no">visionai.assets.get</code></p>
<p><code dir="ltr" translate="no">visionai.assets.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.search</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.clusterEditor" class="role-title add-link" data-text="Vision AI Cluster Editor Beta" tabindex="-1">Vision AI Cluster Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p>Access to read and write Vision AI Cluster.</p></td>
<td><p><code dir="ltr" translate="no">visionai.clusters.create</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.delete</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.get</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.update</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.watch</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.clusterViewer" class="role-title add-link" data-text="Vision AI Cluster Viewer Beta" tabindex="-1">Vision AI Cluster Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.clusterViewer</code> )</p>
<p>Access to read Vision AI Clusters.</p></td>
<td><p><code dir="ltr" translate="no">visionai.clusters.get</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.corpusAdmin" class="role-title add-link" data-text="VisionAI Warehouse Corpus Administrator Beta" tabindex="-1">VisionAI Warehouse Corpus Administrator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p>Full control to everything in a corpus including corpus access control.</p></td>
<td><p><code dir="ltr" translate="no">visionai.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.corpora.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.corpora.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.create</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.delete</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.get</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.import</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.list</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.suggest</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.dataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.dataSchemas.create</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.get</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.list</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.update</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.indexes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexes.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.operations.get</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.searchConfigs.create</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.get</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.list</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.corpusEditor" class="role-title add-link" data-text="VisionAI Warehouse Corpus Editor Beta" tabindex="-1">VisionAI Warehouse Corpus Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p>Read-write access to everything in a corpus.</p></td>
<td><p><code dir="ltr" translate="no">visionai.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.corpora.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.corpora.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.create</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.delete</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.get</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.import</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.list</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.suggest</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.dataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.dataSchemas.create</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.get</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.list</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.update</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.indexes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexes.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.operations.get</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.searchConfigs.create</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.get</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.list</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.corpusViewer" class="role-title add-link" data-text="VisionAI Warehouse Corpus Viewer Beta" tabindex="-1">VisionAI Warehouse Corpus Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Grants access to view everything in a corpus.</p></td>
<td><p><code dir="ltr" translate="no">visionai.annotations.get</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.clip</code></p>
<p><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></p>
<p><code dir="ltr" translate="no">visionai.assets.get</code></p>
<p><code dir="ltr" translate="no">visionai.assets.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.search</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.get</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.list</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.suggest</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.get</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.list</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.get</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></p>
<p><code dir="ltr" translate="no">visionai.operations.get</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.get</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.corpusWriter" class="role-title add-link" data-text="VisionAI Warehouse Corpus Writer Beta" tabindex="-1">VisionAI Warehouse Corpus Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Grants access to create/update/delete everything in a corpus.</p></td>
<td><p><code dir="ltr" translate="no">visionai.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.corpora.analyze</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.delete</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.import</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.update</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.create</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.update</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.create</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.delete</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.update</code></p>
<p><code dir="ltr" translate="no">visionai.operations.get</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.create</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.eventEditor" class="role-title add-link" data-text="Vision AI Event Editor Beta" tabindex="-1">Vision AI Event Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.eventEditor</code> )</p>
<p>Access to read and write Vision AI Events.</p></td>
<td><p><code dir="ltr" translate="no">visionai.events.create</code></p>
<p><code dir="ltr" translate="no">visionai.events.delete</code></p>
<p><code dir="ltr" translate="no">visionai.events.get</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.eventViewer" class="role-title add-link" data-text="Vision AI Event Viewer Beta" tabindex="-1">Vision AI Event Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.eventViewer</code> )</p>
<p>Access to read Vision AI Events.</p></td>
<td><p><code dir="ltr" translate="no">visionai.events.get</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexEndpointAdmin" class="role-title add-link" data-text="VisionAI Warehouse IndexEndpoint Administrator Beta" tabindex="-1">VisionAI Warehouse IndexEndpoint Administrator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p>Full control of all Media Warehouse resources and permissions.</p></td>
<td><p><code dir="ltr" translate="no">visionai.indexEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></li>
<li><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexEndpointEditor" class="role-title add-link" data-text="VisionAI Warehouse IndexEndpoint Editor Beta" tabindex="-1">VisionAI Warehouse IndexEndpoint Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p>Read, write and create access to all index endpoints level resources.</p></td>
<td><p><code dir="ltr" translate="no">visionai.indexEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></li>
<li><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexEndpointViewer" class="role-title add-link" data-text="VisionAI Warehouse IndexEndpoint Viewer Beta" tabindex="-1">VisionAI Warehouse IndexEndpoint Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.indexEndpointViewer</code> )</p>
<p>Grants access to view all index endpoint resources and be able to search on them. (ReadOnly)</p></td>
<td><p><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexEndpointWriter" class="role-title add-link" data-text="VisionAI Warehouse IndexEndpoint Writer Beta" tabindex="-1">VisionAI Warehouse IndexEndpoint Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.indexEndpointWriter</code> )</p>
<p>Grants access to perform update, delete, deploy and undeploy operations on the index endpoint.</p></td>
<td><p><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></p>
<p><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operatorEditor" class="role-title add-link" data-text="Vision AI Operator Editor Beta" tabindex="-1">Vision AI Operator Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.operatorEditor</code> )</p>
<p>Access to read and write Vision AI Operators.</p></td>
<td><p><code dir="ltr" translate="no">visionai.operators.create</code></p>
<p><code dir="ltr" translate="no">visionai.operators.delete</code></p>
<p><code dir="ltr" translate="no">visionai.operators.get</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p>
<p><code dir="ltr" translate="no">visionai.operators.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operatorViewer" class="role-title add-link" data-text="Vision AI Operator Viewer Beta" tabindex="-1">Vision AI Operator Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.operatorViewer</code> )</p>
<p>Access to read Vision AI Operators.</p></td>
<td><p><code dir="ltr" translate="no">visionai.operators.get</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.packetReceiver" class="role-title add-link" data-text="Vision AI Packet Receiver Beta" tabindex="-1">Vision AI Packet Receiver <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p>Access to read Vision AI Series.</p></td>
<td><p><code dir="ltr" translate="no">visionai.clusters.watch</code></p>
<p><code dir="ltr" translate="no">visionai.series.acquireLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.receive</code></p>
<p><code dir="ltr" translate="no">visionai.series.releaseLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.renewLease</code></p>
<p><code dir="ltr" translate="no">visionai.streams.receive</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.packetSender" class="role-title add-link" data-text="Vision AI Packet Sender Beta" tabindex="-1">Vision AI Packet Sender <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.packetSender</code> )</p>
<p>Packet sender to the series.</p></td>
<td><p><code dir="ltr" translate="no">visionai.series.acquireLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.releaseLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.renewLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.send</code></p>
<p><code dir="ltr" translate="no">visionai.streams.send</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.processorEditor" class="role-title add-link" data-text="Vision AI Processor Editor Beta" tabindex="-1">Vision AI Processor Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p>Access to read and write Vision AI Processors.</p></td>
<td><p><code dir="ltr" translate="no">visionai.processors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.processors.create</code></li>
<li><code dir="ltr" translate="no">visionai.processors.delete</code></li>
<li><code dir="ltr" translate="no">visionai.processors.get</code></li>
<li><code dir="ltr" translate="no">visionai.processors.list</code></li>
<li><code dir="ltr" translate="no">visionai.  processors.  listPrebuilt</code></li>
<li><code dir="ltr" translate="no">visionai.processors.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.processorViewer" class="role-title add-link" data-text="Vision AI Processor Viewer Beta" tabindex="-1">Vision AI Processor Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.processorViewer</code> )</p>
<p>Access to read Vision AI Processors.</p></td>
<td><p><code dir="ltr" translate="no">visionai.processors.get</code></p>
<p><code dir="ltr" translate="no">visionai.processors.list</code></p>
<p><code dir="ltr" translate="no">visionai.  processors.  listPrebuilt</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.retailcatalogEditor" class="role-title add-link" data-text="Vision AI RetailCatalog Editor Beta" tabindex="-1">Vision AI RetailCatalog Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.retailcatalogEditor</code> )</p>
<p>Access to read and write Vision AI RetailCatalogs.</p></td>
<td></td>
</tr>
<tr class="even">
<td><h4 id="visionai.retailcatalogViewer" class="role-title add-link" data-text="Vision AI RetailCatalog Viewer Beta" tabindex="-1">Vision AI RetailCatalog Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.retailcatalogViewer</code> )</p>
<p>Access to read Vision AI RetailCatalogs.</p></td>
<td></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.retailendpointEditor" class="role-title add-link" data-text="Vision AI RetailEndpoint Editor Beta" tabindex="-1">Vision AI RetailEndpoint Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.retailendpointEditor</code> )</p>
<p>Access to read and write Vision AI RetailEndpoints.</p></td>
<td></td>
</tr>
<tr class="even">
<td><h4 id="visionai.retailendpointViewer" class="role-title add-link" data-text="Vision AI RetailEndpoint Viewer Beta" tabindex="-1">Vision AI RetailEndpoint Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.retailendpointViewer</code> )</p>
<p>Access to read Vision AI RetailEndpoints.</p></td>
<td></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.seriesEditor" class="role-title add-link" data-text="Vision AI Series Editor Beta" tabindex="-1">Vision AI Series Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p>Access to read and write Vision AI Series.</p></td>
<td><p><code dir="ltr" translate="no">visionai.clusters.watch</code></p>
<p><code dir="ltr" translate="no">visionai.series.acquireLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.create</code></p>
<p><code dir="ltr" translate="no">visionai.series.delete</code></p>
<p><code dir="ltr" translate="no">visionai.series.get</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.receive</code></p>
<p><code dir="ltr" translate="no">visionai.series.releaseLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.renewLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.send</code></p>
<p><code dir="ltr" translate="no">visionai.series.update</code></p>
<p><code dir="ltr" translate="no">visionai.streams.receive</code></p>
<p><code dir="ltr" translate="no">visionai.streams.send</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.seriesViewer" class="role-title add-link" data-text="Vision AI Series Viewer Beta" tabindex="-1">Vision AI Series Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.seriesViewer</code> )</p>
<p>Access to read Vision AI Series.</p></td>
<td><p><code dir="ltr" translate="no">visionai.series.get</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.streamEditor" class="role-title add-link" data-text="Vision AI Stream Editor Beta" tabindex="-1">Vision AI Stream Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Access to read and write Vision AI Streams.</p></td>
<td><p><code dir="ltr" translate="no">visionai.clusters.watch</code></p>
<p><code dir="ltr" translate="no">visionai.series.acquireLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.receive</code></p>
<p><code dir="ltr" translate="no">visionai.series.releaseLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.renewLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.send</code></p>
<p><code dir="ltr" translate="no">visionai.streams.create</code></p>
<p><code dir="ltr" translate="no">visionai.streams.delete</code></p>
<p><code dir="ltr" translate="no">visionai.streams.get</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p>
<p><code dir="ltr" translate="no">visionai.streams.receive</code></p>
<p><code dir="ltr" translate="no">visionai.streams.send</code></p>
<p><code dir="ltr" translate="no">visionai.streams.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.streamViewer" class="role-title add-link" data-text="Vision AI Stream Viewer Beta" tabindex="-1">Vision AI Stream Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.streamViewer</code> )</p>
<p>Access to read Vision AI Streams.</p></td>
<td><p><code dir="ltr" translate="no">visionai.streams.get</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.uiStreamEditor" class="role-title add-link" data-text="Vision AI UI Stream Editor Beta" tabindex="-1">Vision AI UI Stream Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.uiStreamEditor</code> )</p>
<p>Access to read &amp; write Vision AI UI Streams.</p></td>
<td><p><code dir="ltr" translate="no">visionai.uistreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.uistreams.create</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.delete</code></li>
<li><code dir="ltr" translate="no">visionai.  uistreams.  generateStreamThumbnails</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.get</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.uiStreamViewer" class="role-title add-link" data-text="Vision AI UI Stream Viewer Beta" tabindex="-1">Vision AI UI Stream Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.uiStreamViewer</code> )</p>
<p>Access to read Vision AI UI Streams.</p></td>
<td><p><code dir="ltr" translate="no">visionai.uistreams.get</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.list</code></p></td>
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
<td><h4 id="visionai.serviceAgent" class="role-title add-link" data-text="Cloud Vision AI Service Agent" tabindex="-1">Cloud Vision AI Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</p>
<p>Grants Cloud Vision AI service account permissions to manage resources in consumer project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.endpoints.predict</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.export</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.models.export</code></p>
<p><code dir="ltr" translate="no">bigquery.readsessions.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.get</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.list</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.readRows</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.get</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.get</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.routes.invoke</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.create</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.delete</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.get</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.update</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.annotations.create</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.delete</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.get</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.list</code></li>
<li><code dir="ltr" translate="no">visionai.annotations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.applications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.applications.create</code></li>
<li><code dir="ltr" translate="no">visionai.applications.delete</code></li>
<li><code dir="ltr" translate="no">visionai.applications.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.get</code></li>
<li><code dir="ltr" translate="no">visionai.applications.list</code></li>
<li><code dir="ltr" translate="no">visionai.applications.undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.applications.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.assets.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.assets.clip</code></li>
<li><code dir="ltr" translate="no">visionai.assets.create</code></li>
<li><code dir="ltr" translate="no">visionai.assets.delete</code></li>
<li><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></li>
<li><code dir="ltr" translate="no">visionai.assets.get</code></li>
<li><code dir="ltr" translate="no">visionai.assets.index</code></li>
<li><code dir="ltr" translate="no">visionai.assets.ingest</code></li>
<li><code dir="ltr" translate="no">visionai.assets.list</code></li>
<li><code dir="ltr" translate="no">visionai.assets.removeIndex</code></li>
<li><code dir="ltr" translate="no">visionai.assets.search</code></li>
<li><code dir="ltr" translate="no">visionai.assets.update</code></li>
<li><code dir="ltr" translate="no">visionai.assets.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.clusters.create</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.delete</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.get</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.update</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.watch</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.corpora.analyze</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.create</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.delete</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.get</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.import</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.list</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.suggest</code></li>
<li><code dir="ltr" translate="no">visionai.corpora.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.dataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.dataSchemas.create</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.get</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.list</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.update</code></li>
<li><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.drafts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.drafts.create</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.delete</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.get</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.list</code></li>
<li><code dir="ltr" translate="no">visionai.drafts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.events.create</code></p>
<p><code dir="ltr" translate="no">visionai.events.delete</code></p>
<p><code dir="ltr" translate="no">visionai.events.get</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.update</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></li>
<li><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></li>
<li><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.indexes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.indexes.create</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.delete</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.get</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.list</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.update</code></li>
<li><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.instances.get</code></li>
<li><code dir="ltr" translate="no">visionai.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.operations.get</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.operators.create</code></p>
<p><code dir="ltr" translate="no">visionai.operators.delete</code></p>
<p><code dir="ltr" translate="no">visionai.operators.get</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p>
<p><code dir="ltr" translate="no">visionai.operators.update</code></p>
<p><code dir="ltr" translate="no">visionai.processors.create</code></p>
<p><code dir="ltr" translate="no">visionai.processors.delete</code></p>
<p><code dir="ltr" translate="no">visionai.processors.get</code></p>
<p><code dir="ltr" translate="no">visionai.processors.list</code></p>
<p><code dir="ltr" translate="no">visionai.processors.update</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.searchConfigs.create</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.get</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.list</code></li>
<li><code dir="ltr" translate="no">visionai.searchConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">visionai.series.acquireLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.create</code></p>
<p><code dir="ltr" translate="no">visionai.series.delete</code></p>
<p><code dir="ltr" translate="no">visionai.series.get</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.receive</code></p>
<p><code dir="ltr" translate="no">visionai.series.releaseLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.renewLease</code></p>
<p><code dir="ltr" translate="no">visionai.series.send</code></p>
<p><code dir="ltr" translate="no">visionai.series.update</code></p>
<p><code dir="ltr" translate="no">visionai.streams.create</code></p>
<p><code dir="ltr" translate="no">visionai.streams.delete</code></p>
<p><code dir="ltr" translate="no">visionai.streams.get</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p>
<p><code dir="ltr" translate="no">visionai.streams.receive</code></p>
<p><code dir="ltr" translate="no">visionai.streams.send</code></p>
<p><code dir="ltr" translate="no">visionai.streams.update</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">visionai.uistreams.create</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.delete</code></li>
<li><code dir="ltr" translate="no">visionai.  uistreams.  generateStreamThumbnails</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.get</code></li>
<li><code dir="ltr" translate="no">visionai.uistreams.list</code></li>
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
<td><h4 id="visionai.analyses.create" class="permission-name add-link" data-text="visionai.analyses.create" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.analyses.delete" class="permission-name add-link" data-text="visionai.analyses.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.analyses.get" class="permission-name add-link" data-text="visionai.analyses.get" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisViewer">Vision AI Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.analyses.getIamPolicy" class="permission-name add-link" data-text="visionai.analyses.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.analyses.list" class="permission-name add-link" data-text="visionai.analyses.list" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisViewer">Vision AI Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.analyses.setIamPolicy" class="permission-name add-link" data-text="visionai.analyses.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.analyses.update" class="permission-name add-link" data-text="visionai.analyses.update" tabindex="-1"><code dir="ltr" translate="no">visionai.analyses.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.analysisEditor">Vision AI Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.analysisEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.annotations.create" class="permission-name add-link" data-text="visionai.annotations.create" tabindex="-1"><code dir="ltr" translate="no">visionai.annotations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.annotations.delete" class="permission-name add-link" data-text="visionai.annotations.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.annotations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.annotations.get" class="permission-name add-link" data-text="visionai.annotations.get" tabindex="-1"><code dir="ltr" translate="no">visionai.annotations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationViewer">VisionAI Warehouse Annotation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.annotations.list" class="permission-name add-link" data-text="visionai.annotations.list" tabindex="-1"><code dir="ltr" translate="no">visionai.annotations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationViewer">VisionAI Warehouse Annotation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.annotations.update" class="permission-name add-link" data-text="visionai.annotations.update" tabindex="-1"><code dir="ltr" translate="no">visionai.annotations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.annotationEditor">VisionAI Warehouse Annotation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.applications.create" class="permission-name add-link" data-text="visionai.applications.create" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.applications.delete" class="permission-name add-link" data-text="visionai.applications.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.applications.deploy" class="permission-name add-link" data-text="visionai.applications.deploy" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.deploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.applications.get" class="permission-name add-link" data-text="visionai.applications.get" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.applications.list" class="permission-name add-link" data-text="visionai.applications.list" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.applications.undeploy" class="permission-name add-link" data-text="visionai.applications.undeploy" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.undeploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.applications.update" class="permission-name add-link" data-text="visionai.applications.update" tabindex="-1"><code dir="ltr" translate="no">visionai.applications.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.analyze" class="permission-name add-link" data-text="visionai.assets.analyze" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.analyze</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assets.clip" class="permission-name add-link" data-text="visionai.assets.clip" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.clip</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.create" class="permission-name add-link" data-text="visionai.assets.create" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetCreator">VisionAI Warehouse Asset Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assets.delete" class="permission-name add-link" data-text="visionai.assets.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.generateHlsUri" class="permission-name add-link" data-text="visionai.assets.generateHlsUri" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.generateHlsUri</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assets.get" class="permission-name add-link" data-text="visionai.assets.get" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetViewer">VisionAI Warehouse Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.index" class="permission-name add-link" data-text="visionai.assets.index" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.index</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assets.ingest" class="permission-name add-link" data-text="visionai.assets.ingest" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.ingest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetCreator">VisionAI Warehouse Asset Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.list" class="permission-name add-link" data-text="visionai.assets.list" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetViewer">VisionAI Warehouse Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assets.removeIndex" class="permission-name add-link" data-text="visionai.assets.removeIndex" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.removeIndex</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.search" class="permission-name add-link" data-text="visionai.assets.search" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetViewer">VisionAI Warehouse Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.assets.update" class="permission-name add-link" data-text="visionai.assets.update" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.assets.upload" class="permission-name add-link" data-text="visionai.assets.upload" tabindex="-1"><code dir="ltr" translate="no">visionai.assets.upload</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.assetEditor">VisionAI Warehouse Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.assetEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.clusters.create" class="permission-name add-link" data-text="visionai.clusters.create" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.clusters.delete" class="permission-name add-link" data-text="visionai.clusters.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.clusters.get" class="permission-name add-link" data-text="visionai.clusters.get" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterViewer">Vision AI Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.clusters.getIamPolicy" class="permission-name add-link" data-text="visionai.clusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.clusters.list" class="permission-name add-link" data-text="visionai.clusters.list" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterViewer">Vision AI Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.clusters.setIamPolicy" class="permission-name add-link" data-text="visionai.clusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.clusters.update" class="permission-name add-link" data-text="visionai.clusters.update" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.clusters.watch" class="permission-name add-link" data-text="visionai.clusters.watch" tabindex="-1"><code dir="ltr" translate="no">visionai.clusters.watch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.clusterEditor">Vision AI Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.corpora.analyze" class="permission-name add-link" data-text="visionai.corpora.analyze" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.analyze</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.corpora.create" class="permission-name add-link" data-text="visionai.corpora.create" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.corpora.delete" class="permission-name add-link" data-text="visionai.corpora.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.corpora.get" class="permission-name add-link" data-text="visionai.corpora.get" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.corpora.import" class="permission-name add-link" data-text="visionai.corpora.import" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.corpora.list" class="permission-name add-link" data-text="visionai.corpora.list" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.corpora.suggest" class="permission-name add-link" data-text="visionai.corpora.suggest" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.suggest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.corpora.update" class="permission-name add-link" data-text="visionai.corpora.update" tabindex="-1"><code dir="ltr" translate="no">visionai.corpora.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.dataSchemas.create" class="permission-name add-link" data-text="visionai.dataSchemas.create" tabindex="-1"><code dir="ltr" translate="no">visionai.dataSchemas.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.dataSchemas.delete" class="permission-name add-link" data-text="visionai.dataSchemas.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.dataSchemas.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.dataSchemas.get" class="permission-name add-link" data-text="visionai.dataSchemas.get" tabindex="-1"><code dir="ltr" translate="no">visionai.dataSchemas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.dataSchemas.list" class="permission-name add-link" data-text="visionai.dataSchemas.list" tabindex="-1"><code dir="ltr" translate="no">visionai.dataSchemas.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.dataSchemas.update" class="permission-name add-link" data-text="visionai.dataSchemas.update" tabindex="-1"><code dir="ltr" translate="no">visionai.dataSchemas.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.dataSchemas.validate" class="permission-name add-link" data-text="visionai.dataSchemas.validate" tabindex="-1"><code dir="ltr" translate="no">visionai.dataSchemas.validate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.drafts.create" class="permission-name add-link" data-text="visionai.drafts.create" tabindex="-1"><code dir="ltr" translate="no">visionai.drafts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.drafts.delete" class="permission-name add-link" data-text="visionai.drafts.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.drafts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.drafts.get" class="permission-name add-link" data-text="visionai.drafts.get" tabindex="-1"><code dir="ltr" translate="no">visionai.drafts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.drafts.list" class="permission-name add-link" data-text="visionai.drafts.list" tabindex="-1"><code dir="ltr" translate="no">visionai.drafts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.drafts.update" class="permission-name add-link" data-text="visionai.drafts.update" tabindex="-1"><code dir="ltr" translate="no">visionai.drafts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.events.create" class="permission-name add-link" data-text="visionai.events.create" tabindex="-1"><code dir="ltr" translate="no">visionai.events.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.events.delete" class="permission-name add-link" data-text="visionai.events.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.events.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.events.get" class="permission-name add-link" data-text="visionai.events.get" tabindex="-1"><code dir="ltr" translate="no">visionai.events.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventViewer">Vision AI Event Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.events.getIamPolicy" class="permission-name add-link" data-text="visionai.events.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.events.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.events.list" class="permission-name add-link" data-text="visionai.events.list" tabindex="-1"><code dir="ltr" translate="no">visionai.events.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventViewer">Vision AI Event Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.events.setIamPolicy" class="permission-name add-link" data-text="visionai.events.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.events.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.events.update" class="permission-name add-link" data-text="visionai.events.update" tabindex="-1"><code dir="ltr" translate="no">visionai.events.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.eventEditor">Vision AI Event Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.eventEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexEndpoints.create" class="permission-name add-link" data-text="visionai.indexEndpoints.create" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexEndpoints.delete" class="permission-name add-link" data-text="visionai.indexEndpoints.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexEndpoints.deploy" class="permission-name add-link" data-text="visionai.indexEndpoints.deploy" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.deploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexEndpoints.get" class="permission-name add-link" data-text="visionai.indexEndpoints.get" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointViewer">VisionAI Warehouse IndexEndpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexEndpoints.list" class="permission-name add-link" data-text="visionai.indexEndpoints.list" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointViewer">VisionAI Warehouse IndexEndpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexEndpoints.search" class="permission-name add-link" data-text="visionai.indexEndpoints.search" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointViewer">VisionAI Warehouse IndexEndpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexEndpoints.undeploy" class="permission-name add-link" data-text="visionai.indexEndpoints.undeploy" tabindex="-1"><code dir="ltr" translate="no">visionai.  indexEndpoints.  undeploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexEndpoints.update" class="permission-name add-link" data-text="visionai.indexEndpoints.update" tabindex="-1"><code dir="ltr" translate="no">visionai.indexEndpoints.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointAdmin">VisionAI Warehouse IndexEndpoint Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointEditor">VisionAI Warehouse IndexEndpoint Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.indexEndpointWriter">VisionAI Warehouse IndexEndpoint Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.indexEndpointWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexes.create" class="permission-name add-link" data-text="visionai.indexes.create" tabindex="-1"><code dir="ltr" translate="no">visionai.indexes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexes.delete" class="permission-name add-link" data-text="visionai.indexes.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.indexes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexes.get" class="permission-name add-link" data-text="visionai.indexes.get" tabindex="-1"><code dir="ltr" translate="no">visionai.indexes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexes.list" class="permission-name add-link" data-text="visionai.indexes.list" tabindex="-1"><code dir="ltr" translate="no">visionai.indexes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.indexes.update" class="permission-name add-link" data-text="visionai.indexes.update" tabindex="-1"><code dir="ltr" translate="no">visionai.indexes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.indexes.viewAssets" class="permission-name add-link" data-text="visionai.indexes.viewAssets" tabindex="-1"><code dir="ltr" translate="no">visionai.indexes.viewAssets</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.instances.get" class="permission-name add-link" data-text="visionai.instances.get" tabindex="-1"><code dir="ltr" translate="no">visionai.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.instances.list" class="permission-name add-link" data-text="visionai.instances.list" tabindex="-1"><code dir="ltr" translate="no">visionai.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationEditor">Vision AI Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.applicationViewer">Vision AI Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.applicationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.locations.get" class="permission-name add-link" data-text="visionai.locations.get" tabindex="-1"><code dir="ltr" translate="no">visionai.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.locations.list" class="permission-name add-link" data-text="visionai.locations.list" tabindex="-1"><code dir="ltr" translate="no">visionai.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operations.cancel" class="permission-name add-link" data-text="visionai.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">visionai.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operations.delete" class="permission-name add-link" data-text="visionai.operations.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operations.get" class="permission-name add-link" data-text="visionai.operations.get" tabindex="-1"><code dir="ltr" translate="no">visionai.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operations.list" class="permission-name add-link" data-text="visionai.operations.list" tabindex="-1"><code dir="ltr" translate="no">visionai.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operations.wait" class="permission-name add-link" data-text="visionai.operations.wait" tabindex="-1"><code dir="ltr" translate="no">visionai.operations.wait</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operators.create" class="permission-name add-link" data-text="visionai.operators.create" tabindex="-1"><code dir="ltr" translate="no">visionai.operators.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operators.delete" class="permission-name add-link" data-text="visionai.operators.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.operators.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operators.get" class="permission-name add-link" data-text="visionai.operators.get" tabindex="-1"><code dir="ltr" translate="no">visionai.operators.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorViewer">Vision AI Operator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operators.getIamPolicy" class="permission-name add-link" data-text="visionai.operators.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.  operators.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operators.list" class="permission-name add-link" data-text="visionai.operators.list" tabindex="-1"><code dir="ltr" translate="no">visionai.operators.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorViewer">Vision AI Operator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.operators.setIamPolicy" class="permission-name add-link" data-text="visionai.operators.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.  operators.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.operators.update" class="permission-name add-link" data-text="visionai.operators.update" tabindex="-1"><code dir="ltr" translate="no">visionai.operators.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.operatorEditor">Vision AI Operator Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.operatorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.processors.create" class="permission-name add-link" data-text="visionai.processors.create" tabindex="-1"><code dir="ltr" translate="no">visionai.processors.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.processors.delete" class="permission-name add-link" data-text="visionai.processors.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.processors.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.processors.get" class="permission-name add-link" data-text="visionai.processors.get" tabindex="-1"><code dir="ltr" translate="no">visionai.processors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorViewer">Vision AI Processor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.processors.list" class="permission-name add-link" data-text="visionai.processors.list" tabindex="-1"><code dir="ltr" translate="no">visionai.processors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorViewer">Vision AI Processor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.processors.listPrebuilt" class="permission-name add-link" data-text="visionai.processors.listPrebuilt" tabindex="-1"><code dir="ltr" translate="no">visionai.  processors.  listPrebuilt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorViewer">Vision AI Processor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.processors.update" class="permission-name add-link" data-text="visionai.processors.update" tabindex="-1"><code dir="ltr" translate="no">visionai.processors.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.processorEditor">Vision AI Processor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.processorEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.searchConfigs.create" class="permission-name add-link" data-text="visionai.searchConfigs.create" tabindex="-1"><code dir="ltr" translate="no">visionai.searchConfigs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.searchConfigs.delete" class="permission-name add-link" data-text="visionai.searchConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.searchConfigs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.searchConfigs.get" class="permission-name add-link" data-text="visionai.searchConfigs.get" tabindex="-1"><code dir="ltr" translate="no">visionai.searchConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.searchConfigs.list" class="permission-name add-link" data-text="visionai.searchConfigs.list" tabindex="-1"><code dir="ltr" translate="no">visionai.searchConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusViewer">VisionAI Warehouse Corpus Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.searchConfigs.update" class="permission-name add-link" data-text="visionai.searchConfigs.update" tabindex="-1"><code dir="ltr" translate="no">visionai.searchConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusAdmin">VisionAI Warehouse Corpus Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusEditor">VisionAI Warehouse Corpus Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.corpusWriter">VisionAI Warehouse Corpus Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.corpusWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.series.acquireLease" class="permission-name add-link" data-text="visionai.series.acquireLease" tabindex="-1"><code dir="ltr" translate="no">visionai.series.acquireLease</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.series.create" class="permission-name add-link" data-text="visionai.series.create" tabindex="-1"><code dir="ltr" translate="no">visionai.series.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.series.delete" class="permission-name add-link" data-text="visionai.series.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.series.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.series.get" class="permission-name add-link" data-text="visionai.series.get" tabindex="-1"><code dir="ltr" translate="no">visionai.series.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesViewer">Vision AI Series Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.series.getIamPolicy" class="permission-name add-link" data-text="visionai.series.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.series.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.series.list" class="permission-name add-link" data-text="visionai.series.list" tabindex="-1"><code dir="ltr" translate="no">visionai.series.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesViewer">Vision AI Series Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.series.receive" class="permission-name add-link" data-text="visionai.series.receive" tabindex="-1"><code dir="ltr" translate="no">visionai.series.receive</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.series.releaseLease" class="permission-name add-link" data-text="visionai.series.releaseLease" tabindex="-1"><code dir="ltr" translate="no">visionai.series.releaseLease</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.series.renewLease" class="permission-name add-link" data-text="visionai.series.renewLease" tabindex="-1"><code dir="ltr" translate="no">visionai.series.renewLease</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.series.send" class="permission-name add-link" data-text="visionai.series.send" tabindex="-1"><code dir="ltr" translate="no">visionai.series.send</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.series.setIamPolicy" class="permission-name add-link" data-text="visionai.series.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.series.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.series.update" class="permission-name add-link" data-text="visionai.series.update" tabindex="-1"><code dir="ltr" translate="no">visionai.series.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.streams.create" class="permission-name add-link" data-text="visionai.streams.create" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.streams.delete" class="permission-name add-link" data-text="visionai.streams.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.streams.get" class="permission-name add-link" data-text="visionai.streams.get" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamViewer">Vision AI Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.streams.getIamPolicy" class="permission-name add-link" data-text="visionai.streams.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.streams.list" class="permission-name add-link" data-text="visionai.streams.list" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamViewer">Vision AI Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.streams.receive" class="permission-name add-link" data-text="visionai.streams.receive" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.receive</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetReceiver">Vision AI Packet Receiver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetReceiver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.streams.send" class="permission-name add-link" data-text="visionai.streams.send" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.send</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.packetSender">Vision AI Packet Sender</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.packetSender</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.seriesEditor">Vision AI Series Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.seriesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.streams.setIamPolicy" class="permission-name add-link" data-text="visionai.streams.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="visionai.streams.update" class="permission-name add-link" data-text="visionai.streams.update" tabindex="-1"><code dir="ltr" translate="no">visionai.streams.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.streamEditor">Vision AI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.streamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.uistreams.create" class="permission-name add-link" data-text="visionai.uistreams.create" tabindex="-1"><code dir="ltr" translate="no">visionai.uistreams.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.uistreams.delete" class="permission-name add-link" data-text="visionai.uistreams.delete" tabindex="-1"><code dir="ltr" translate="no">visionai.uistreams.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.uistreams.generateStreamThumbnails" class="permission-name add-link" data-text="visionai.uistreams.generateStreamThumbnails" tabindex="-1"><code dir="ltr" translate="no">visionai.  uistreams.  generateStreamThumbnails</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="visionai.uistreams.get" class="permission-name add-link" data-text="visionai.uistreams.get" tabindex="-1"><code dir="ltr" translate="no">visionai.uistreams.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamViewer">Vision AI UI Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="visionai.uistreams.list" class="permission-name add-link" data-text="visionai.uistreams.list" tabindex="-1"><code dir="ltr" translate="no">visionai.uistreams.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamEditor">Vision AI UI Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.uiStreamViewer">Vision AI UI Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.uiStreamViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
