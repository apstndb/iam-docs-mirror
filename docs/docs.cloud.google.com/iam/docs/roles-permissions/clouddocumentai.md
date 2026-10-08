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
<td>Document AI Administrator <sup>Beta</sup>
<p>( <code>roles/ documentai.admin</code> )</p>
<p>Grants full access to all resources in Document AI</p></td>
<td><p><code>documentai.*</code></p>
<ul>
<li><code>documentai. dataLabelingJobs. cancel</code></li>
<li><code>documentai. dataLabelingJobs. create</code></li>
<li><code>documentai. dataLabelingJobs. list</code></li>
<li><code>documentai.datasetSchemas.get</code></li>
<li><code>documentai. datasetSchemas. update</code></li>
<li><code>documentai. datasets. createDocuments</code></li>
<li><code>documentai. datasets. deleteDocuments</code></li>
<li><code>documentai.datasets.get</code></li>
<li><code>documentai. datasets. getDocuments</code></li>
<li><code>documentai. datasets. listDocuments</code></li>
<li><code>documentai.datasets.update</code></li>
<li><code>documentai. datasets. updateDocuments</code></li>
<li><code>documentai. evaluationDocuments. get</code></li>
<li><code>documentai.evaluations.create</code></li>
<li><code>documentai.evaluations.get</code></li>
<li><code>documentai.evaluations.list</code></li>
<li><code>documentai. humanReviewConfigs. get</code></li>
<li><code>documentai. humanReviewConfigs. review</code></li>
<li><code>documentai. humanReviewConfigs. update</code></li>
<li><code>documentai.labelerPools.create</code></li>
<li><code>documentai.labelerPools.delete</code></li>
<li><code>documentai.labelerPools.get</code></li>
<li><code>documentai.labelerPools.list</code></li>
<li><code>documentai.locations.get</code></li>
<li><code>documentai.locations.list</code></li>
<li><code>documentai. operations. getLegacy</code></li>
<li><code>documentai. processedDocumentsSets. get</code></li>
<li><code>documentai. processedDocumentsSets. getDocuments</code></li>
<li><code>documentai. processedDocumentsSets. listDocuments</code></li>
<li><code>documentai.processorTypes.get</code></li>
<li><code>documentai.processorTypes.list</code></li>
<li><code>documentai. processorVersions. create</code></li>
<li><code>documentai. processorVersions. delete</code></li>
<li><code>documentai. processorVersions. get</code></li>
<li><code>documentai. processorVersions. list</code></li>
<li><code>documentai. processorVersions. processBatch</code></li>
<li><code>documentai. processorVersions. processOnline</code></li>
<li><code>documentai. processorVersions. update</code></li>
<li><code>documentai.processors.create</code></li>
<li><code>documentai.processors.delete</code></li>
<li><code>documentai. processors. fetchHumanReviewDetails</code></li>
<li><code>documentai.processors.get</code></li>
<li><code>documentai.processors.list</code></li>
<li><code>documentai. processors. processBatch</code></li>
<li><code>documentai. processors. processOnline</code></li>
<li><code>documentai.processors.update</code></li>
<li><code>documentai.rules.create</code></li>
<li><code>documentai.rules.delete</code></li>
<li><code>documentai.rules.generate</code></li>
<li><code>documentai.rules.get</code></li>
<li><code>documentai.rules.list</code></li>
<li><code>documentai.rules.update</code></li>
<li><code>documentai. schemaVersions. create</code></li>
<li><code>documentai. schemaVersions. delete</code></li>
<li><code>documentai.schemaVersions.get</code></li>
<li><code>documentai.schemaVersions.list</code></li>
<li><code>documentai. schemaVersions. update</code></li>
<li><code>documentai.schemas.create</code></li>
<li><code>documentai.schemas.delete</code></li>
<li><code>documentai.schemas.get</code></li>
<li><code>documentai.schemas.list</code></li>
<li><code>documentai.schemas.update</code></li>
<li><code>documentai.validators.create</code></li>
<li><code>documentai.validators.delete</code></li>
<li><code>documentai.validators.get</code></li>
<li><code>documentai.validators.list</code></li>
<li><code>documentai.validators.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Document AI Editor <sup>Beta</sup>
<p>( <code>roles/ documentai.editor</code> )</p>
<p>Grants access to use all resources in Document AI</p></td>
<td><p><code>documentai.*</code></p>
<ul>
<li><code>documentai. dataLabelingJobs. cancel</code></li>
<li><code>documentai. dataLabelingJobs. create</code></li>
<li><code>documentai. dataLabelingJobs. list</code></li>
<li><code>documentai.datasetSchemas.get</code></li>
<li><code>documentai. datasetSchemas. update</code></li>
<li><code>documentai. datasets. createDocuments</code></li>
<li><code>documentai. datasets. deleteDocuments</code></li>
<li><code>documentai.datasets.get</code></li>
<li><code>documentai. datasets. getDocuments</code></li>
<li><code>documentai. datasets. listDocuments</code></li>
<li><code>documentai.datasets.update</code></li>
<li><code>documentai. datasets. updateDocuments</code></li>
<li><code>documentai. evaluationDocuments. get</code></li>
<li><code>documentai.evaluations.create</code></li>
<li><code>documentai.evaluations.get</code></li>
<li><code>documentai.evaluations.list</code></li>
<li><code>documentai. humanReviewConfigs. get</code></li>
<li><code>documentai. humanReviewConfigs. review</code></li>
<li><code>documentai. humanReviewConfigs. update</code></li>
<li><code>documentai.labelerPools.create</code></li>
<li><code>documentai.labelerPools.delete</code></li>
<li><code>documentai.labelerPools.get</code></li>
<li><code>documentai.labelerPools.list</code></li>
<li><code>documentai.locations.get</code></li>
<li><code>documentai.locations.list</code></li>
<li><code>documentai. operations. getLegacy</code></li>
<li><code>documentai. processedDocumentsSets. get</code></li>
<li><code>documentai. processedDocumentsSets. getDocuments</code></li>
<li><code>documentai. processedDocumentsSets. listDocuments</code></li>
<li><code>documentai.processorTypes.get</code></li>
<li><code>documentai.processorTypes.list</code></li>
<li><code>documentai. processorVersions. create</code></li>
<li><code>documentai. processorVersions. delete</code></li>
<li><code>documentai. processorVersions. get</code></li>
<li><code>documentai. processorVersions. list</code></li>
<li><code>documentai. processorVersions. processBatch</code></li>
<li><code>documentai. processorVersions. processOnline</code></li>
<li><code>documentai. processorVersions. update</code></li>
<li><code>documentai.processors.create</code></li>
<li><code>documentai.processors.delete</code></li>
<li><code>documentai. processors. fetchHumanReviewDetails</code></li>
<li><code>documentai.processors.get</code></li>
<li><code>documentai.processors.list</code></li>
<li><code>documentai. processors. processBatch</code></li>
<li><code>documentai. processors. processOnline</code></li>
<li><code>documentai.processors.update</code></li>
<li><code>documentai.rules.create</code></li>
<li><code>documentai.rules.delete</code></li>
<li><code>documentai.rules.generate</code></li>
<li><code>documentai.rules.get</code></li>
<li><code>documentai.rules.list</code></li>
<li><code>documentai.rules.update</code></li>
<li><code>documentai. schemaVersions. create</code></li>
<li><code>documentai. schemaVersions. delete</code></li>
<li><code>documentai.schemaVersions.get</code></li>
<li><code>documentai.schemaVersions.list</code></li>
<li><code>documentai. schemaVersions. update</code></li>
<li><code>documentai.schemas.create</code></li>
<li><code>documentai.schemas.delete</code></li>
<li><code>documentai.schemas.get</code></li>
<li><code>documentai.schemas.list</code></li>
<li><code>documentai.schemas.update</code></li>
<li><code>documentai.validators.create</code></li>
<li><code>documentai.validators.delete</code></li>
<li><code>documentai.validators.get</code></li>
<li><code>documentai.validators.list</code></li>
<li><code>documentai.validators.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Document AI Viewer <sup>Beta</sup>
<p>( <code>roles/ documentai.viewer</code> )</p>
<p>Grants access to view all resources and process documents in Document AI</p></td>
<td><p><code>documentai. dataLabelingJobs. list</code></p>
<p><code>documentai.datasetSchemas.get</code></p>
<p><code>documentai.datasets.get</code></p>
<p><code>documentai. datasets. getDocuments</code></p>
<p><code>documentai. datasets. listDocuments</code></p>
<p><code>documentai. evaluationDocuments. get</code></p>
<p><code>documentai.evaluations.get</code></p>
<p><code>documentai.evaluations.list</code></p>
<p><code>documentai. humanReviewConfigs. get</code></p>
<p><code>documentai. humanReviewConfigs. review</code></p>
<p><code>documentai.labelerPools.get</code></p>
<p><code>documentai.labelerPools.list</code></p>
<p><code>documentai.locations.*</code></p>
<ul>
<li><code>documentai.locations.get</code></li>
<li><code>documentai.locations.list</code></li>
</ul>
<p><code>documentai. operations. getLegacy</code></p>
<p><code>documentai. processedDocumentsSets.*</code></p>
<ul>
<li><code>documentai. processedDocumentsSets. get</code></li>
<li><code>documentai. processedDocumentsSets. getDocuments</code></li>
<li><code>documentai. processedDocumentsSets. listDocuments</code></li>
</ul>
<p><code>documentai.processorTypes.*</code></p>
<ul>
<li><code>documentai.processorTypes.get</code></li>
<li><code>documentai.processorTypes.list</code></li>
</ul>
<p><code>documentai. processorVersions. get</code></p>
<p><code>documentai. processorVersions. list</code></p>
<p><code>documentai. processorVersions. processBatch</code></p>
<p><code>documentai. processorVersions. processOnline</code></p>
<p><code>documentai. processors. fetchHumanReviewDetails</code></p>
<p><code>documentai.processors.get</code></p>
<p><code>documentai.processors.list</code></p>
<p><code>documentai. processors. processBatch</code></p>
<p><code>documentai. processors. processOnline</code></p>
<p><code>documentai.rules.get</code></p>
<p><code>documentai.rules.list</code></p>
<p><code>documentai.schemaVersions.get</code></p>
<p><code>documentai.schemaVersions.list</code></p>
<p><code>documentai.schemas.get</code></p>
<p><code>documentai.schemas.list</code></p>
<p><code>documentai.validators.get</code></p>
<p><code>documentai.validators.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Document AI API User <sup>Beta</sup>
<p>( <code>roles/ documentai.apiUser</code> )</p>
<p>Grants access to process documents in Document AI</p></td>
<td><p><code>documentai. humanReviewConfigs. review</code></p>
<p><code>documentai. operations. getLegacy</code></p>
<p><code>documentai. processorVersions. processBatch</code></p>
<p><code>documentai. processorVersions. processOnline</code></p>
<p><code>documentai. processors. processBatch</code></p>
<p><code>documentai. processors. processOnline</code></p></td>
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
<td>DocumentAI Core Service Agent
<p>( <code>roles/ documentaicore.serviceAgent</code> )</p>
<p>Gives DocumentAI Core Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>automl.models.predict</code></p>
<p><code>documentai. humanReviewConfigs. review</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
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
<td><code>documentai. dataLabelingJobs. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. dataLabelingJobs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. dataLabelingJobs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.datasetSchemas.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. datasetSchemas. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. datasets. createDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>documentai. datasets. deleteDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.datasets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. datasets. getDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. datasets. listDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.datasets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. datasets. updateDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. evaluationDocuments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.evaluations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.evaluations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.evaluations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. humanReviewConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. humanReviewConfigs. review</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code>roles/ documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a> ( <code>roles/ documentaicore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>documentai. humanReviewConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.labelerPools.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.labelerPools.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.labelerPools.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.labelerPools.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. operations. getLegacy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code>roles/ documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. processedDocumentsSets. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. processedDocumentsSets. getDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. processedDocumentsSets. listDocuments</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.processorTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.processorTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. processorVersions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. processorVersions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. processorVersions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. processorVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. processorVersions. processBatch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code>roles/ documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. processorVersions. processOnline</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code>roles/ documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>documentai. processorVersions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.processors.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.processors.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. processors. fetchHumanReviewDetails</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.processors.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>documentai.processors.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. processors. processBatch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code>roles/ documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>documentai. processors. processOnline</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.apiUser">Document AI API User</a> ( <code>roles/ documentai.apiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>documentai.processors.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.rules.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.rules.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.rules.generate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.rules.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.rules.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.rules.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. schemaVersions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai. schemaVersions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.schemaVersions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.schemaVersions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai. schemaVersions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.schemas.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.schemas.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.schemas.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.schemas.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.schemas.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.validators.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.validators.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.validators.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>documentai.validators.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>documentai.validators.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p></td>
</tr>
</tbody>
</table>
