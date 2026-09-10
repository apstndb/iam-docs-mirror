---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai
title: Document AI roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Document AI. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Document AI roles

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
<td><h4 id="documentai.admin" class="role-title add-link" data-text="Document AI Administrator Beta" tabindex="-1">Document AI Administrator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p>Grants full access to all resources in Document AI</p></td>
<td><p><code dir="ltr" translate="no">documentai.*</code></p>
<ul>
<li><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  cancel</code></li>
<li><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  create</code></li>
<li><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  list</code></li>
<li><code dir="ltr" translate="no">documentai.datasetSchemas.get</code></li>
<li><code dir="ltr" translate="no">documentai.  datasetSchemas.  update</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  createDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  deleteDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.datasets.get</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  getDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  listDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.datasets.update</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  updateDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  evaluationDocuments.  get</code></li>
<li><code dir="ltr" translate="no">documentai.evaluations.create</code></li>
<li><code dir="ltr" translate="no">documentai.evaluations.get</code></li>
<li><code dir="ltr" translate="no">documentai.evaluations.list</code></li>
<li><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  review</code></li>
<li><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  update</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.create</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.delete</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.get</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.list</code></li>
<li><code dir="ltr" translate="no">documentai.locations.get</code></li>
<li><code dir="ltr" translate="no">documentai.locations.list</code></li>
<li><code dir="ltr" translate="no">documentai.  operations.  getLegacy</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  getDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  listDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.processorTypes.get</code></li>
<li><code dir="ltr" translate="no">documentai.processorTypes.list</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  create</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  delete</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  list</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  processBatch</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  processOnline</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  update</code></li>
<li><code dir="ltr" translate="no">documentai.processors.create</code></li>
<li><code dir="ltr" translate="no">documentai.processors.delete</code></li>
<li><code dir="ltr" translate="no">documentai.  processors.  fetchHumanReviewDetails</code></li>
<li><code dir="ltr" translate="no">documentai.processors.get</code></li>
<li><code dir="ltr" translate="no">documentai.processors.list</code></li>
<li><code dir="ltr" translate="no">documentai.  processors.  processBatch</code></li>
<li><code dir="ltr" translate="no">documentai.  processors.  processOnline</code></li>
<li><code dir="ltr" translate="no">documentai.processors.update</code></li>
<li><code dir="ltr" translate="no">documentai.rules.create</code></li>
<li><code dir="ltr" translate="no">documentai.rules.delete</code></li>
<li><code dir="ltr" translate="no">documentai.rules.generate</code></li>
<li><code dir="ltr" translate="no">documentai.rules.get</code></li>
<li><code dir="ltr" translate="no">documentai.rules.list</code></li>
<li><code dir="ltr" translate="no">documentai.rules.update</code></li>
<li><code dir="ltr" translate="no">documentai.  schemaVersions.  create</code></li>
<li><code dir="ltr" translate="no">documentai.  schemaVersions.  delete</code></li>
<li><code dir="ltr" translate="no">documentai.schemaVersions.get</code></li>
<li><code dir="ltr" translate="no">documentai.schemaVersions.list</code></li>
<li><code dir="ltr" translate="no">documentai.  schemaVersions.  update</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.create</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.delete</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.get</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.list</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.update</code></li>
<li><code dir="ltr" translate="no">documentai.validators.create</code></li>
<li><code dir="ltr" translate="no">documentai.validators.delete</code></li>
<li><code dir="ltr" translate="no">documentai.validators.get</code></li>
<li><code dir="ltr" translate="no">documentai.validators.list</code></li>
<li><code dir="ltr" translate="no">documentai.validators.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.editor" class="role-title add-link" data-text="Document AI Editor Beta" tabindex="-1">Document AI Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p>Grants access to use all resources in Document AI</p></td>
<td><p><code dir="ltr" translate="no">documentai.*</code></p>
<ul>
<li><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  cancel</code></li>
<li><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  create</code></li>
<li><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  list</code></li>
<li><code dir="ltr" translate="no">documentai.datasetSchemas.get</code></li>
<li><code dir="ltr" translate="no">documentai.  datasetSchemas.  update</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  createDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  deleteDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.datasets.get</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  getDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  listDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.datasets.update</code></li>
<li><code dir="ltr" translate="no">documentai.  datasets.  updateDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  evaluationDocuments.  get</code></li>
<li><code dir="ltr" translate="no">documentai.evaluations.create</code></li>
<li><code dir="ltr" translate="no">documentai.evaluations.get</code></li>
<li><code dir="ltr" translate="no">documentai.evaluations.list</code></li>
<li><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  review</code></li>
<li><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  update</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.create</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.delete</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.get</code></li>
<li><code dir="ltr" translate="no">documentai.labelerPools.list</code></li>
<li><code dir="ltr" translate="no">documentai.locations.get</code></li>
<li><code dir="ltr" translate="no">documentai.locations.list</code></li>
<li><code dir="ltr" translate="no">documentai.  operations.  getLegacy</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  getDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  listDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.processorTypes.get</code></li>
<li><code dir="ltr" translate="no">documentai.processorTypes.list</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  create</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  delete</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  list</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  processBatch</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  processOnline</code></li>
<li><code dir="ltr" translate="no">documentai.  processorVersions.  update</code></li>
<li><code dir="ltr" translate="no">documentai.processors.create</code></li>
<li><code dir="ltr" translate="no">documentai.processors.delete</code></li>
<li><code dir="ltr" translate="no">documentai.  processors.  fetchHumanReviewDetails</code></li>
<li><code dir="ltr" translate="no">documentai.processors.get</code></li>
<li><code dir="ltr" translate="no">documentai.processors.list</code></li>
<li><code dir="ltr" translate="no">documentai.  processors.  processBatch</code></li>
<li><code dir="ltr" translate="no">documentai.  processors.  processOnline</code></li>
<li><code dir="ltr" translate="no">documentai.processors.update</code></li>
<li><code dir="ltr" translate="no">documentai.rules.create</code></li>
<li><code dir="ltr" translate="no">documentai.rules.delete</code></li>
<li><code dir="ltr" translate="no">documentai.rules.generate</code></li>
<li><code dir="ltr" translate="no">documentai.rules.get</code></li>
<li><code dir="ltr" translate="no">documentai.rules.list</code></li>
<li><code dir="ltr" translate="no">documentai.rules.update</code></li>
<li><code dir="ltr" translate="no">documentai.  schemaVersions.  create</code></li>
<li><code dir="ltr" translate="no">documentai.  schemaVersions.  delete</code></li>
<li><code dir="ltr" translate="no">documentai.schemaVersions.get</code></li>
<li><code dir="ltr" translate="no">documentai.schemaVersions.list</code></li>
<li><code dir="ltr" translate="no">documentai.  schemaVersions.  update</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.create</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.delete</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.get</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.list</code></li>
<li><code dir="ltr" translate="no">documentai.schemas.update</code></li>
<li><code dir="ltr" translate="no">documentai.validators.create</code></li>
<li><code dir="ltr" translate="no">documentai.validators.delete</code></li>
<li><code dir="ltr" translate="no">documentai.validators.get</code></li>
<li><code dir="ltr" translate="no">documentai.validators.list</code></li>
<li><code dir="ltr" translate="no">documentai.validators.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.viewer" class="role-title add-link" data-text="Document AI Viewer Beta" tabindex="-1">Document AI Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p>Grants access to view all resources and process documents in Document AI</p></td>
<td><p><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">documentai.datasetSchemas.get</code></p>
<p><code dir="ltr" translate="no">documentai.datasets.get</code></p>
<p><code dir="ltr" translate="no">documentai.  datasets.  getDocuments</code></p>
<p><code dir="ltr" translate="no">documentai.  datasets.  listDocuments</code></p>
<p><code dir="ltr" translate="no">documentai.  evaluationDocuments.  get</code></p>
<p><code dir="ltr" translate="no">documentai.evaluations.get</code></p>
<p><code dir="ltr" translate="no">documentai.evaluations.list</code></p>
<p><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  get</code></p>
<p><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  review</code></p>
<p><code dir="ltr" translate="no">documentai.labelerPools.get</code></p>
<p><code dir="ltr" translate="no">documentai.labelerPools.list</code></p>
<p><code dir="ltr" translate="no">documentai.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">documentai.locations.get</code></li>
<li><code dir="ltr" translate="no">documentai.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">documentai.  operations.  getLegacy</code></p>
<p><code dir="ltr" translate="no">documentai.  processedDocumentsSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  get</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  getDocuments</code></li>
<li><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  listDocuments</code></li>
</ul>
<p><code dir="ltr" translate="no">documentai.processorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">documentai.processorTypes.get</code></li>
<li><code dir="ltr" translate="no">documentai.processorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  get</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  list</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  processBatch</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  processOnline</code></p>
<p><code dir="ltr" translate="no">documentai.  processors.  fetchHumanReviewDetails</code></p>
<p><code dir="ltr" translate="no">documentai.processors.get</code></p>
<p><code dir="ltr" translate="no">documentai.processors.list</code></p>
<p><code dir="ltr" translate="no">documentai.  processors.  processBatch</code></p>
<p><code dir="ltr" translate="no">documentai.  processors.  processOnline</code></p>
<p><code dir="ltr" translate="no">documentai.rules.get</code></p>
<p><code dir="ltr" translate="no">documentai.rules.list</code></p>
<p><code dir="ltr" translate="no">documentai.schemaVersions.get</code></p>
<p><code dir="ltr" translate="no">documentai.schemaVersions.list</code></p>
<p><code dir="ltr" translate="no">documentai.schemas.get</code></p>
<p><code dir="ltr" translate="no">documentai.schemas.list</code></p>
<p><code dir="ltr" translate="no">documentai.validators.get</code></p>
<p><code dir="ltr" translate="no">documentai.validators.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.apiUser" class="role-title add-link" data-text="Document AI API User Beta" tabindex="-1">Document AI API User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p>Grants access to process documents in Document AI</p></td>
<td><p><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  review</code></p>
<p><code dir="ltr" translate="no">documentai.  operations.  getLegacy</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  processBatch</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  processOnline</code></p>
<p><code dir="ltr" translate="no">documentai.  processors.  processBatch</code></p>
<p><code dir="ltr" translate="no">documentai.  processors.  processOnline</code></p></td>
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
<td><h4 id="documentaicore.serviceAgent" class="role-title add-link" data-text="DocumentAI Core Service Agent" tabindex="-1">DocumentAI Core Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</p>
<p>Gives DocumentAI Core Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  review</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Document AI permissions

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
<td><h4 id="documentai.dataLabelingJobs.cancel" class="permission-name add-link" data-text="documentai.dataLabelingJobs.cancel" tabindex="-1"><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.dataLabelingJobs.create" class="permission-name add-link" data-text="documentai.dataLabelingJobs.create" tabindex="-1"><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.dataLabelingJobs.list" class="permission-name add-link" data-text="documentai.dataLabelingJobs.list" tabindex="-1"><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.datasetSchemas.get" class="permission-name add-link" data-text="documentai.datasetSchemas.get" tabindex="-1"><code dir="ltr" translate="no">documentai.datasetSchemas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.datasetSchemas.update" class="permission-name add-link" data-text="documentai.datasetSchemas.update" tabindex="-1"><code dir="ltr" translate="no">documentai.  datasetSchemas.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.datasets.createDocuments" class="permission-name add-link" data-text="documentai.datasets.createDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  datasets.  createDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.datasets.deleteDocuments" class="permission-name add-link" data-text="documentai.datasets.deleteDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  datasets.  deleteDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.datasets.get" class="permission-name add-link" data-text="documentai.datasets.get" tabindex="-1"><code dir="ltr" translate="no">documentai.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.datasets.getDocuments" class="permission-name add-link" data-text="documentai.datasets.getDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  datasets.  getDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.datasets.listDocuments" class="permission-name add-link" data-text="documentai.datasets.listDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  datasets.  listDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.datasets.update" class="permission-name add-link" data-text="documentai.datasets.update" tabindex="-1"><code dir="ltr" translate="no">documentai.datasets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.datasets.updateDocuments" class="permission-name add-link" data-text="documentai.datasets.updateDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  datasets.  updateDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.evaluationDocuments.get" class="permission-name add-link" data-text="documentai.evaluationDocuments.get" tabindex="-1"><code dir="ltr" translate="no">documentai.  evaluationDocuments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.evaluations.create" class="permission-name add-link" data-text="documentai.evaluations.create" tabindex="-1"><code dir="ltr" translate="no">documentai.evaluations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.evaluations.get" class="permission-name add-link" data-text="documentai.evaluations.get" tabindex="-1"><code dir="ltr" translate="no">documentai.evaluations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.evaluations.list" class="permission-name add-link" data-text="documentai.evaluations.list" tabindex="-1"><code dir="ltr" translate="no">documentai.evaluations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.humanReviewConfigs.get" class="permission-name add-link" data-text="documentai.humanReviewConfigs.get" tabindex="-1"><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.humanReviewConfigs.review" class="permission-name add-link" data-text="documentai.humanReviewConfigs.review" tabindex="-1"><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  review</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentaicore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.humanReviewConfigs.update" class="permission-name add-link" data-text="documentai.humanReviewConfigs.update" tabindex="-1"><code dir="ltr" translate="no">documentai.  humanReviewConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.labelerPools.create" class="permission-name add-link" data-text="documentai.labelerPools.create" tabindex="-1"><code dir="ltr" translate="no">documentai.labelerPools.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.labelerPools.delete" class="permission-name add-link" data-text="documentai.labelerPools.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.labelerPools.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.labelerPools.get" class="permission-name add-link" data-text="documentai.labelerPools.get" tabindex="-1"><code dir="ltr" translate="no">documentai.labelerPools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.labelerPools.list" class="permission-name add-link" data-text="documentai.labelerPools.list" tabindex="-1"><code dir="ltr" translate="no">documentai.labelerPools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.locations.get" class="permission-name add-link" data-text="documentai.locations.get" tabindex="-1"><code dir="ltr" translate="no">documentai.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.locations.list" class="permission-name add-link" data-text="documentai.locations.list" tabindex="-1"><code dir="ltr" translate="no">documentai.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.operations.getLegacy" class="permission-name add-link" data-text="documentai.operations.getLegacy" tabindex="-1"><code dir="ltr" translate="no">documentai.  operations.  getLegacy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processedDocumentsSets.get" class="permission-name add-link" data-text="documentai.processedDocumentsSets.get" tabindex="-1"><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processedDocumentsSets.getDocuments" class="permission-name add-link" data-text="documentai.processedDocumentsSets.getDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  getDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processedDocumentsSets.listDocuments" class="permission-name add-link" data-text="documentai.processedDocumentsSets.listDocuments" tabindex="-1"><code dir="ltr" translate="no">documentai.  processedDocumentsSets.  listDocuments</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processorTypes.get" class="permission-name add-link" data-text="documentai.processorTypes.get" tabindex="-1"><code dir="ltr" translate="no">documentai.processorTypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processorTypes.list" class="permission-name add-link" data-text="documentai.processorTypes.list" tabindex="-1"><code dir="ltr" translate="no">documentai.processorTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processorVersions.create" class="permission-name add-link" data-text="documentai.processorVersions.create" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processorVersions.delete" class="permission-name add-link" data-text="documentai.processorVersions.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processorVersions.get" class="permission-name add-link" data-text="documentai.processorVersions.get" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processorVersions.list" class="permission-name add-link" data-text="documentai.processorVersions.list" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processorVersions.processBatch" class="permission-name add-link" data-text="documentai.processorVersions.processBatch" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  processBatch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processorVersions.processOnline" class="permission-name add-link" data-text="documentai.processorVersions.processOnline" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  processOnline</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processorVersions.update" class="permission-name add-link" data-text="documentai.processorVersions.update" tabindex="-1"><code dir="ltr" translate="no">documentai.  processorVersions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processors.create" class="permission-name add-link" data-text="documentai.processors.create" tabindex="-1"><code dir="ltr" translate="no">documentai.processors.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processors.delete" class="permission-name add-link" data-text="documentai.processors.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.processors.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processors.fetchHumanReviewDetails" class="permission-name add-link" data-text="documentai.processors.fetchHumanReviewDetails" tabindex="-1"><code dir="ltr" translate="no">documentai.  processors.  fetchHumanReviewDetails</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processors.get" class="permission-name add-link" data-text="documentai.processors.get" tabindex="-1"><code dir="ltr" translate="no">documentai.processors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processors.list" class="permission-name add-link" data-text="documentai.processors.list" tabindex="-1"><code dir="ltr" translate="no">documentai.processors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processors.processBatch" class="permission-name add-link" data-text="documentai.processors.processBatch" tabindex="-1"><code dir="ltr" translate="no">documentai.  processors.  processBatch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.processors.processOnline" class="permission-name add-link" data-text="documentai.processors.processOnline" tabindex="-1"><code dir="ltr" translate="no">documentai.  processors.  processOnline</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="documentai.processors.update" class="permission-name add-link" data-text="documentai.processors.update" tabindex="-1"><code dir="ltr" translate="no">documentai.processors.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.rules.create" class="permission-name add-link" data-text="documentai.rules.create" tabindex="-1"><code dir="ltr" translate="no">documentai.rules.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.rules.delete" class="permission-name add-link" data-text="documentai.rules.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.rules.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.rules.generate" class="permission-name add-link" data-text="documentai.rules.generate" tabindex="-1"><code dir="ltr" translate="no">documentai.rules.generate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.rules.get" class="permission-name add-link" data-text="documentai.rules.get" tabindex="-1"><code dir="ltr" translate="no">documentai.rules.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.rules.list" class="permission-name add-link" data-text="documentai.rules.list" tabindex="-1"><code dir="ltr" translate="no">documentai.rules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.rules.update" class="permission-name add-link" data-text="documentai.rules.update" tabindex="-1"><code dir="ltr" translate="no">documentai.rules.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.schemaVersions.create" class="permission-name add-link" data-text="documentai.schemaVersions.create" tabindex="-1"><code dir="ltr" translate="no">documentai.  schemaVersions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.schemaVersions.delete" class="permission-name add-link" data-text="documentai.schemaVersions.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.  schemaVersions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.schemaVersions.get" class="permission-name add-link" data-text="documentai.schemaVersions.get" tabindex="-1"><code dir="ltr" translate="no">documentai.schemaVersions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.schemaVersions.list" class="permission-name add-link" data-text="documentai.schemaVersions.list" tabindex="-1"><code dir="ltr" translate="no">documentai.schemaVersions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.schemaVersions.update" class="permission-name add-link" data-text="documentai.schemaVersions.update" tabindex="-1"><code dir="ltr" translate="no">documentai.  schemaVersions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.schemas.create" class="permission-name add-link" data-text="documentai.schemas.create" tabindex="-1"><code dir="ltr" translate="no">documentai.schemas.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.schemas.delete" class="permission-name add-link" data-text="documentai.schemas.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.schemas.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.schemas.get" class="permission-name add-link" data-text="documentai.schemas.get" tabindex="-1"><code dir="ltr" translate="no">documentai.schemas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.schemas.list" class="permission-name add-link" data-text="documentai.schemas.list" tabindex="-1"><code dir="ltr" translate="no">documentai.schemas.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.schemas.update" class="permission-name add-link" data-text="documentai.schemas.update" tabindex="-1"><code dir="ltr" translate="no">documentai.schemas.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.validators.create" class="permission-name add-link" data-text="documentai.validators.create" tabindex="-1"><code dir="ltr" translate="no">documentai.validators.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.validators.delete" class="permission-name add-link" data-text="documentai.validators.delete" tabindex="-1"><code dir="ltr" translate="no">documentai.validators.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.validators.get" class="permission-name add-link" data-text="documentai.validators.get" tabindex="-1"><code dir="ltr" translate="no">documentai.validators.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="documentai.validators.list" class="permission-name add-link" data-text="documentai.validators.list" tabindex="-1"><code dir="ltr" translate="no">documentai.validators.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="documentai.validators.update" class="permission-name add-link" data-text="documentai.validators.update" tabindex="-1"><code dir="ltr" translate="no">documentai.validators.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  documentai.editor</code> )</p></td>
</tr>
</tbody>
</table>
