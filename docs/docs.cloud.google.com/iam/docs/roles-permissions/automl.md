---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/automl
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/automl
title: AutoML roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for AutoML. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## AutoML roles

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
<td><h4 id="automl.admin" class="role-title add-link" data-text="AutoML Admin Beta" tabindex="-1">AutoML Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p>Full access to all AutoML resources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Dataset</li>
<li>Model</li>
</ul></td>
<td><p><code dir="ltr" translate="no">automl.*</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="automl.editor" class="role-title add-link" data-text="AutoML Editor Beta" tabindex="-1">AutoML Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p>Editor of all AutoML resources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Dataset</li>
<li>Model</li>
</ul></td>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="automl.viewer" class="role-title add-link" data-text="AutoML Viewer Beta" tabindex="-1">AutoML Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p>Viewer of all AutoML resources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Dataset</li>
<li>Model</li>
</ul></td>
<td><p><code dir="ltr" translate="no">automl.annotationSpecs.get</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="automl.predictor" class="role-title add-link" data-text="AutoML Predictor Beta" tabindex="-1">AutoML Predictor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automl.predictor</code> )</p>
<p>Predict using models</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Model</li>
</ul></td>
<td><p><code dir="ltr" translate="no">automl.models.predict</code></p>
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
<td><h4 id="automl.serviceAgent" class="role-title add-link" data-text="AutoML Service Agent" tabindex="-1">AutoML Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  automl.serviceAgent</code> )</p>
<p>AutoML service agent can act as Cloud Storage admin and export BigQuery tables, which can be backed by Cloud Storage and Cloud Bigtable.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.get</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.list</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.readRows</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## AutoML permissions

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
<td><h4 id="automl.annotationSpecs.create" class="permission-name add-link" data-text="automl.annotationSpecs.create" tabindex="-1"><code dir="ltr" translate="no">automl.annotationSpecs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.annotationSpecs.delete" class="permission-name add-link" data-text="automl.annotationSpecs.delete" tabindex="-1"><code dir="ltr" translate="no">automl.annotationSpecs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.annotationSpecs.get" class="permission-name add-link" data-text="automl.annotationSpecs.get" tabindex="-1"><code dir="ltr" translate="no">automl.annotationSpecs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.annotationSpecs.list" class="permission-name add-link" data-text="automl.annotationSpecs.list" tabindex="-1"><code dir="ltr" translate="no">automl.annotationSpecs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.annotationSpecs.update" class="permission-name add-link" data-text="automl.annotationSpecs.update" tabindex="-1"><code dir="ltr" translate="no">automl.annotationSpecs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.annotations.approve" class="permission-name add-link" data-text="automl.annotations.approve" tabindex="-1"><code dir="ltr" translate="no">automl.annotations.approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.annotations.create" class="permission-name add-link" data-text="automl.annotations.create" tabindex="-1"><code dir="ltr" translate="no">automl.annotations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.annotations.list" class="permission-name add-link" data-text="automl.annotations.list" tabindex="-1"><code dir="ltr" translate="no">automl.annotations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.annotations.manipulate" class="permission-name add-link" data-text="automl.annotations.manipulate" tabindex="-1"><code dir="ltr" translate="no">automl.annotations.manipulate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.annotations.reject" class="permission-name add-link" data-text="automl.annotations.reject" tabindex="-1"><code dir="ltr" translate="no">automl.annotations.reject</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.columnSpecs.get" class="permission-name add-link" data-text="automl.columnSpecs.get" tabindex="-1"><code dir="ltr" translate="no">automl.columnSpecs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.columnSpecs.list" class="permission-name add-link" data-text="automl.columnSpecs.list" tabindex="-1"><code dir="ltr" translate="no">automl.columnSpecs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.columnSpecs.update" class="permission-name add-link" data-text="automl.columnSpecs.update" tabindex="-1"><code dir="ltr" translate="no">automl.columnSpecs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.datasets.create" class="permission-name add-link" data-text="automl.datasets.create" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.datasets.delete" class="permission-name add-link" data-text="automl.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.datasets.export" class="permission-name add-link" data-text="automl.datasets.export" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.datasets.get" class="permission-name add-link" data-text="automl.datasets.get" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.datasets.getIamPolicy" class="permission-name add-link" data-text="automl.datasets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automl.datasets.import" class="permission-name add-link" data-text="automl.datasets.import" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.datasets.list" class="permission-name add-link" data-text="automl.datasets.list" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.datasets.setIamPolicy" class="permission-name add-link" data-text="automl.datasets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automl.datasets.update" class="permission-name add-link" data-text="automl.datasets.update" tabindex="-1"><code dir="ltr" translate="no">automl.datasets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.examples.delete" class="permission-name add-link" data-text="automl.examples.delete" tabindex="-1"><code dir="ltr" translate="no">automl.examples.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.examples.get" class="permission-name add-link" data-text="automl.examples.get" tabindex="-1"><code dir="ltr" translate="no">automl.examples.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.examples.list" class="permission-name add-link" data-text="automl.examples.list" tabindex="-1"><code dir="ltr" translate="no">automl.examples.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.examples.update" class="permission-name add-link" data-text="automl.examples.update" tabindex="-1"><code dir="ltr" translate="no">automl.examples.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.files.delete" class="permission-name add-link" data-text="automl.files.delete" tabindex="-1"><code dir="ltr" translate="no">automl.files.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.files.list" class="permission-name add-link" data-text="automl.files.list" tabindex="-1"><code dir="ltr" translate="no">automl.files.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.humanAnnotationTasks.create" class="permission-name add-link" data-text="automl.humanAnnotationTasks.create" tabindex="-1"><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.humanAnnotationTasks.delete" class="permission-name add-link" data-text="automl.humanAnnotationTasks.delete" tabindex="-1"><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.humanAnnotationTasks.get" class="permission-name add-link" data-text="automl.humanAnnotationTasks.get" tabindex="-1"><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.humanAnnotationTasks.list" class="permission-name add-link" data-text="automl.humanAnnotationTasks.list" tabindex="-1"><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.locations.get" class="permission-name add-link" data-text="automl.locations.get" tabindex="-1"><code dir="ltr" translate="no">automl.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.locations.getIamPolicy" class="permission-name add-link" data-text="automl.locations.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">automl.locations.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automl.locations.list" class="permission-name add-link" data-text="automl.locations.list" tabindex="-1"><code dir="ltr" translate="no">automl.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.locations.setIamPolicy" class="permission-name add-link" data-text="automl.locations.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">automl.locations.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automl.modelEvaluations.create" class="permission-name add-link" data-text="automl.modelEvaluations.create" tabindex="-1"><code dir="ltr" translate="no">automl.modelEvaluations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.modelEvaluations.get" class="permission-name add-link" data-text="automl.modelEvaluations.get" tabindex="-1"><code dir="ltr" translate="no">automl.modelEvaluations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.modelEvaluations.list" class="permission-name add-link" data-text="automl.modelEvaluations.list" tabindex="-1"><code dir="ltr" translate="no">automl.modelEvaluations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
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
<td><h4 id="automl.models.create" class="permission-name add-link" data-text="automl.models.create" tabindex="-1"><code dir="ltr" translate="no">automl.models.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.models.delete" class="permission-name add-link" data-text="automl.models.delete" tabindex="-1"><code dir="ltr" translate="no">automl.models.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.models.deploy" class="permission-name add-link" data-text="automl.models.deploy" tabindex="-1"><code dir="ltr" translate="no">automl.models.deploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.models.export" class="permission-name add-link" data-text="automl.models.export" tabindex="-1"><code dir="ltr" translate="no">automl.models.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.models.get" class="permission-name add-link" data-text="automl.models.get" tabindex="-1"><code dir="ltr" translate="no">automl.models.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.models.getIamPolicy" class="permission-name add-link" data-text="automl.models.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">automl.models.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automl.models.list" class="permission-name add-link" data-text="automl.models.list" tabindex="-1"><code dir="ltr" translate="no">automl.models.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.models.predict" class="permission-name add-link" data-text="automl.models.predict" tabindex="-1"><code dir="ltr" translate="no">automl.models.predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.predictor">AutoML Predictor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.predictor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.models.setIamPolicy" class="permission-name add-link" data-text="automl.models.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">automl.models.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automl.models.undeploy" class="permission-name add-link" data-text="automl.models.undeploy" tabindex="-1"><code dir="ltr" translate="no">automl.models.undeploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.operations.cancel" class="permission-name add-link" data-text="automl.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">automl.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.operations.delete" class="permission-name add-link" data-text="automl.operations.delete" tabindex="-1"><code dir="ltr" translate="no">automl.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.operations.get" class="permission-name add-link" data-text="automl.operations.get" tabindex="-1"><code dir="ltr" translate="no">automl.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtranslate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="automl.operations.list" class="permission-name add-link" data-text="automl.operations.list" tabindex="-1"><code dir="ltr" translate="no">automl.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.tableSpecs.get" class="permission-name add-link" data-text="automl.tableSpecs.get" tabindex="-1"><code dir="ltr" translate="no">automl.tableSpecs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
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
<td><h4 id="automl.tableSpecs.list" class="permission-name add-link" data-text="automl.tableSpecs.list" tabindex="-1"><code dir="ltr" translate="no">automl.tableSpecs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalabeling.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="automl.tableSpecs.update" class="permission-name add-link" data-text="automl.tableSpecs.update" tabindex="-1"><code dir="ltr" translate="no">automl.tableSpecs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
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
