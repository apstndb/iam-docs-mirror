---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datalabeling
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling
title: AI Platform Data Labeling Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for AI Platform Data Labeling Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## AI Platform Data Labeling Service roles

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
<td><h4 id="datalabeling.admin" class="role-title add-link" data-text="Data Labeling Service Admin Beta" tabindex="-1">Data Labeling Service Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p>Full access to all Data Labeling resources</p></td>
<td><p><code dir="ltr" translate="no">datalabeling.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  get</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  label</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  list</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  create</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  get</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  list</code></li>
<li><code dir="ltr" translate="no">datalabeling.dataitems.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.dataitems.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.create</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.export</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.import</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.examples.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.examples.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.  instructions.  create</code></li>
<li><code dir="ltr" translate="no">datalabeling.  instructions.  delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.instructions.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.instructions.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datalabeling.operations.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.editor" class="role-title add-link" data-text="Data Labeling Service Editor Beta" tabindex="-1">Data Labeling Service Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p>Editor of all Data Labeling resources</p></td>
<td><p><code dir="ltr" translate="no">datalabeling.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  get</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  label</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  list</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  create</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  get</code></li>
<li><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  list</code></li>
<li><code dir="ltr" translate="no">datalabeling.dataitems.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.dataitems.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.create</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.export</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.import</code></li>
<li><code dir="ltr" translate="no">datalabeling.datasets.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.examples.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.examples.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.  instructions.  create</code></li>
<li><code dir="ltr" translate="no">datalabeling.  instructions.  delete</code></li>
<li><code dir="ltr" translate="no">datalabeling.instructions.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.instructions.list</code></li>
<li><code dir="ltr" translate="no">datalabeling.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datalabeling.operations.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.viewer" class="role-title add-link" data-text="Data Labeling Service Viewer Beta" tabindex="-1">Data Labeling Service Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p>Viewer of all Data Labeling resources</p></td>
<td><p><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  get</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  list</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  get</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  list</code></p>
<p><code dir="ltr" translate="no">datalabeling.dataitems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalabeling.dataitems.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.dataitems.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datalabeling.datasets.get</code></p>
<p><code dir="ltr" translate="no">datalabeling.datasets.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.examples.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalabeling.examples.get</code></li>
<li><code dir="ltr" translate="no">datalabeling.examples.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datalabeling.instructions.get</code></p>
<p><code dir="ltr" translate="no">datalabeling.instructions.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.operations.get</code></p>
<p><code dir="ltr" translate="no">datalabeling.operations.list</code></p>
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
<td><h4 id="datalabeling.serviceAgent" class="role-title add-link" data-text="Data Labeling Service Agent" tabindex="-1">Data Labeling Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</p>
<p>Gives Data Labeling service account read/write access to Cloud Storage, read/write BigQuery, update CMLE model versions, editor access to Annotation service and AutoML service.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">automl.annotationSpecs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.annotationSpecs.create</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.delete</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.annotationSpecs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.annotations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.annotations.approve</code></li>
<li><code dir="ltr" translate="no">automl.annotations.create</code></li>
<li><code dir="ltr" translate="no">automl.annotations.list</code></li>
<li><code dir="ltr" translate="no">automl.annotations.manipulate</code></li>
<li><code dir="ltr" translate="no">automl.annotations.reject</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.columnSpecs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.columnSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.columnSpecs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.datasets.create</code></p>
<p><code dir="ltr" translate="no">automl.datasets.delete</code></p>
<p><code dir="ltr" translate="no">automl.datasets.export</code></p>
<p><code dir="ltr" translate="no">automl.datasets.get</code></p>
<p><code dir="ltr" translate="no">automl.datasets.import</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.update</code></p>
<p><code dir="ltr" translate="no">automl.examples.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.examples.delete</code></li>
<li><code dir="ltr" translate="no">automl.examples.get</code></li>
<li><code dir="ltr" translate="no">automl.examples.list</code></li>
<li><code dir="ltr" translate="no">automl.examples.update</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.files.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.files.delete</code></li>
<li><code dir="ltr" translate="no">automl.files.list</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.humanAnnotationTasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  create</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  delete</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></li>
<li><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.locations.get</code></p>
<p><code dir="ltr" translate="no">automl.locations.list</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.modelEvaluations.create</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.get</code></li>
<li><code dir="ltr" translate="no">automl.modelEvaluations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.models.create</code></p>
<p><code dir="ltr" translate="no">automl.models.delete</code></p>
<p><code dir="ltr" translate="no">automl.models.deploy</code></p>
<p><code dir="ltr" translate="no">automl.models.export</code></p>
<p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">automl.models.undeploy</code></p>
<p><code dir="ltr" translate="no">automl.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.operations.cancel</code></li>
<li><code dir="ltr" translate="no">automl.operations.delete</code></li>
<li><code dir="ltr" translate="no">automl.operations.get</code></li>
<li><code dir="ltr" translate="no">automl.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">automl.tableSpecs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automl.tableSpecs.get</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.list</code></li>
<li><code dir="ltr" translate="no">automl.tableSpecs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">ml.jobs.create</code></p>
<p><code dir="ltr" translate="no">ml.jobs.get</code></p>
<p><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.jobs.list</code></p>
<p><code dir="ltr" translate="no">ml.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.locations.get</code></li>
<li><code dir="ltr" translate="no">ml.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">ml.models.*</code></p>
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
<p><code dir="ltr" translate="no">ml.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ml.versions.create</code></li>
<li><code dir="ltr" translate="no">ml.versions.delete</code></li>
<li><code dir="ltr" translate="no">ml.versions.get</code></li>
<li><code dir="ltr" translate="no">ml.versions.list</code></li>
<li><code dir="ltr" translate="no">ml.versions.predict</code></li>
<li><code dir="ltr" translate="no">ml.versions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## AI Platform Data Labeling Service permissions

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
<td><h4 id="datalabeling.annotateddatasets.delete" class="permission-name add-link" data-text="datalabeling.annotateddatasets.delete" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.annotateddatasets.get" class="permission-name add-link" data-text="datalabeling.annotateddatasets.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.annotateddatasets.label" class="permission-name add-link" data-text="datalabeling.annotateddatasets.label" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  label</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.annotateddatasets.list" class="permission-name add-link" data-text="datalabeling.annotateddatasets.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.annotationspecsets.create" class="permission-name add-link" data-text="datalabeling.annotationspecsets.create" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.annotationspecsets.delete" class="permission-name add-link" data-text="datalabeling.annotationspecsets.delete" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.annotationspecsets.get" class="permission-name add-link" data-text="datalabeling.annotationspecsets.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.annotationspecsets.list" class="permission-name add-link" data-text="datalabeling.annotationspecsets.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.dataitems.get" class="permission-name add-link" data-text="datalabeling.dataitems.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.dataitems.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.dataitems.list" class="permission-name add-link" data-text="datalabeling.dataitems.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.dataitems.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.datasets.create" class="permission-name add-link" data-text="datalabeling.datasets.create" tabindex="-1"><code dir="ltr" translate="no">datalabeling.datasets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.datasets.delete" class="permission-name add-link" data-text="datalabeling.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">datalabeling.datasets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.datasets.export" class="permission-name add-link" data-text="datalabeling.datasets.export" tabindex="-1"><code dir="ltr" translate="no">datalabeling.datasets.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.datasets.get" class="permission-name add-link" data-text="datalabeling.datasets.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.datasets.import" class="permission-name add-link" data-text="datalabeling.datasets.import" tabindex="-1"><code dir="ltr" translate="no">datalabeling.datasets.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.datasets.list" class="permission-name add-link" data-text="datalabeling.datasets.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.datasets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.examples.get" class="permission-name add-link" data-text="datalabeling.examples.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.examples.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.examples.list" class="permission-name add-link" data-text="datalabeling.examples.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.examples.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.instructions.create" class="permission-name add-link" data-text="datalabeling.instructions.create" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  instructions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.instructions.delete" class="permission-name add-link" data-text="datalabeling.instructions.delete" tabindex="-1"><code dir="ltr" translate="no">datalabeling.  instructions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.instructions.get" class="permission-name add-link" data-text="datalabeling.instructions.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.instructions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.instructions.list" class="permission-name add-link" data-text="datalabeling.instructions.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.instructions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.operations.cancel" class="permission-name add-link" data-text="datalabeling.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">datalabeling.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalabeling.operations.get" class="permission-name add-link" data-text="datalabeling.operations.get" tabindex="-1"><code dir="ltr" translate="no">datalabeling.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datalabeling.operations.list" class="permission-name add-link" data-text="datalabeling.operations.list" tabindex="-1"><code dir="ltr" translate="no">datalabeling.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
