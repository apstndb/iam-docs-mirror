---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate
title: Translation roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Translation. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Translation roles

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
<td><h4 id="cloudtranslate.admin" class="role-title add-link" data-text="Cloud Translation API Admin" tabindex="-1">Cloud Translation API Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p>Full access to all Cloud Translation resources</p></td>
<td><p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  import</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.export</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.import</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchDocPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  docPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchDocPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  docPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  update</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  update</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  languageDetectionModels.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.locations.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.operations.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.operations.wait</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.editor" class="role-title add-link" data-text="Cloud Translation API Editor" tabindex="-1">Cloud Translation API Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p>Editor of all Cloud Translation resources</p></td>
<td><p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  import</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  customModels.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.export</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.import</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchDocPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  docPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchDocPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  docPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaries.  update</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  create</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  update</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  languageDetectionModels.  predict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.locations.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.operations.list</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.operations.wait</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.user" class="role-title add-link" data-text="Cloud Translation API User" tabindex="-1">Cloud Translation API User</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p>User of Cloud Translation and AutoML models</p></td>
<td><p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.datasets.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.generalModels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchDocPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  docPredict</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.  generalModels.  predict</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchDocPredict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchPredict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  docPredict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  languageDetectionModels.  predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtranslate.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtranslate.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.operations.wait</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.viewer" class="role-title add-link" data-text="Cloud Translation API Viewer" tabindex="-1">Cloud Translation API Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p>Viewer of all Translation resources</p></td>
<td><p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.datasets.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  generalModels.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtranslate.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtranslate.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtranslate.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.operations.wait</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="cloudtranslate.serviceAgent" class="role-title add-link" data-text="Cloud Translation API Service Agent" tabindex="-1">Cloud Translation API Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</p>
<p>Gives Cloud Translation Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">automl.datasets.export</code></p>
<p><code dir="ltr" translate="no">automl.datasets.get</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.operations.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Translation permissions

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
<td><h4 id="cloudtranslate.adaptiveMtDatasets.create" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtDatasets.create" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.adaptiveMtDatasets.delete" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtDatasets.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.adaptiveMtDatasets.get" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtDatasets.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.adaptiveMtDatasets.import" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtDatasets.import" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.adaptiveMtDatasets.list" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtDatasets.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.adaptiveMtDatasets.predict" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtDatasets.predict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.adaptiveMtFiles.delete" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtFiles.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.adaptiveMtFiles.get" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtFiles.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.adaptiveMtFiles.list" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtFiles.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.adaptiveMtSentences.list" class="permission-name add-link" data-text="cloudtranslate.adaptiveMtSentences.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.customModels.create" class="permission-name add-link" data-text="cloudtranslate.customModels.create" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  customModels.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.customModels.delete" class="permission-name add-link" data-text="cloudtranslate.customModels.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  customModels.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.customModels.get" class="permission-name add-link" data-text="cloudtranslate.customModels.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.customModels.list" class="permission-name add-link" data-text="cloudtranslate.customModels.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.customModels.predict" class="permission-name add-link" data-text="cloudtranslate.customModels.predict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  customModels.  predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.datasets.create" class="permission-name add-link" data-text="cloudtranslate.datasets.create" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.datasets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.datasets.delete" class="permission-name add-link" data-text="cloudtranslate.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.datasets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.datasets.export" class="permission-name add-link" data-text="cloudtranslate.datasets.export" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.datasets.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.datasets.get" class="permission-name add-link" data-text="cloudtranslate.datasets.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.datasets.import" class="permission-name add-link" data-text="cloudtranslate.datasets.import" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.datasets.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.datasets.list" class="permission-name add-link" data-text="cloudtranslate.datasets.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.generalModels.batchDocPredict" class="permission-name add-link" data-text="cloudtranslate.generalModels.batchDocPredict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchDocPredict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.generalModels.batchPredict" class="permission-name add-link" data-text="cloudtranslate.generalModels.batchPredict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  generalModels.  batchPredict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.generalModels.docPredict" class="permission-name add-link" data-text="cloudtranslate.generalModels.docPredict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  generalModels.  docPredict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.generalModels.get" class="permission-name add-link" data-text="cloudtranslate.generalModels.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  generalModels.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.generalModels.predict" class="permission-name add-link" data-text="cloudtranslate.generalModels.predict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  generalModels.  predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaries.batchDocPredict" class="permission-name add-link" data-text="cloudtranslate.glossaries.batchDocPredict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchDocPredict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaries.batchPredict" class="permission-name add-link" data-text="cloudtranslate.glossaries.batchPredict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  batchPredict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaries.create" class="permission-name add-link" data-text="cloudtranslate.glossaries.create" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaries.delete" class="permission-name add-link" data-text="cloudtranslate.glossaries.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaries.docPredict" class="permission-name add-link" data-text="cloudtranslate.glossaries.docPredict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  docPredict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaries.get" class="permission-name add-link" data-text="cloudtranslate.glossaries.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaries.list" class="permission-name add-link" data-text="cloudtranslate.glossaries.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaries.predict" class="permission-name add-link" data-text="cloudtranslate.glossaries.predict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaries.update" class="permission-name add-link" data-text="cloudtranslate.glossaries.update" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaries.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaryentries.create" class="permission-name add-link" data-text="cloudtranslate.glossaryentries.create" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaryentries.delete" class="permission-name add-link" data-text="cloudtranslate.glossaryentries.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaryentries.get" class="permission-name add-link" data-text="cloudtranslate.glossaryentries.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.glossaryentries.list" class="permission-name add-link" data-text="cloudtranslate.glossaryentries.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.glossaryentries.update" class="permission-name add-link" data-text="cloudtranslate.glossaryentries.update" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.languageDetectionModels.predict" class="permission-name add-link" data-text="cloudtranslate.languageDetectionModels.predict" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  languageDetectionModels.  predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.locations.get" class="permission-name add-link" data-text="cloudtranslate.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.locations.list" class="permission-name add-link" data-text="cloudtranslate.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.operations.cancel" class="permission-name add-link" data-text="cloudtranslate.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.operations.delete" class="permission-name add-link" data-text="cloudtranslate.operations.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.operations.get" class="permission-name add-link" data-text="cloudtranslate.operations.get" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtranslate.operations.list" class="permission-name add-link" data-text="cloudtranslate.operations.list" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtranslate.operations.wait" class="permission-name add-link" data-text="cloudtranslate.operations.wait" tabindex="-1"><code dir="ltr" translate="no">cloudtranslate.operations.wait</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
