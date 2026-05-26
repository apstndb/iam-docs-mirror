---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse
title: Content Warehouse roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Content Warehouse. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Content Warehouse roles

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
<td><h4 id="contentwarehouse.admin" class="role-title add-link" data-text="Content Warehouse Admin" tabindex="-1">Content Warehouse Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p>Grants full access to all the resources in Content Warehouse</p></td>
<td><p><code dir="ltr" translate="no">contentwarehouse.corpora.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  corpora.  create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  corpora.  delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.corpora.get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.corpora.list</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  corpora.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.  dataExportJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  dataExportJobs.  create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  dataExportJobs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  list</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.documents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  documents.  create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documents.  delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.documents.get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documents.  list</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documents.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  documents.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  locations.  initialize</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.  operations.  get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  download</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  upload</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.ruleSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  ruleSets.  create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  ruleSets.  delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.ruleSets.get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.ruleSets.list</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  ruleSets.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.synonymSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  list</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documentAdmin" class="role-title add-link" data-text="Content Warehouse Document Admin" tabindex="-1">Content Warehouse Document Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p>Grants full access to the document resource in Content Warehouse</p></td>
<td><p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  create</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  delete</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.documents.get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  update</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.links.create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.links.delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.links.get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.links.update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  download</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  upload</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documentCreator" class="role-title add-link" data-text="Content Warehouse document creator" tabindex="-1">Content Warehouse document creator</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p>
<p>Grants access to create document in Content Warehouse</p></td>
<td><p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  create</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documentEditor" class="role-title add-link" data-text="Content Warehouse Document Editor" tabindex="-1">Content Warehouse Document Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p>Grants access to update document resource in Content Warehouse</p></td>
<td><p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.documents.get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  update</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.links.create</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.links.delete</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.links.get</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.links.update</code></li>
</ul>
<p><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  download</code></li>
<li><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  upload</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documentSchemaViewer" class="role-title add-link" data-text="Content Warehouse document schema viewer" tabindex="-1">Content Warehouse document schema viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.documentSchemaViewer</code> )</p>
<p>Grants access to view the document schemas in Content Warehouse</p></td>
<td><p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documentViewer" class="role-title add-link" data-text="Content Warehouse Viewer" tabindex="-1">Content Warehouse Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p>Grants access to view all the resources in Content Warehouse</p></td>
<td><p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.documents.get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.links.get</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  download</code></p>
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
<td><h4 id="contentwarehouse.serviceAgent" class="role-title add-link" data-text="Content Warehouse Service Agent" tabindex="-1">Content Warehouse Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</p>
<p>Gives the Content Warehouse service account to manage customer resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">documentai.  datasets.  createDocuments</code></p>
<p><code dir="ltr" translate="no">documentai.processors.get</code></p>
<p><code dir="ltr" translate="no">documentai.  processors.  processBatch</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.publish</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Content Warehouse permissions

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
<td><h4 id="contentwarehouse.corpora.create" class="permission-name add-link" data-text="contentwarehouse.corpora.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  corpora.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.corpora.delete" class="permission-name add-link" data-text="contentwarehouse.corpora.delete" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  corpora.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.corpora.get" class="permission-name add-link" data-text="contentwarehouse.corpora.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.corpora.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.corpora.list" class="permission-name add-link" data-text="contentwarehouse.corpora.list" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.corpora.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.corpora.update" class="permission-name add-link" data-text="contentwarehouse.corpora.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  corpora.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.dataExportJobs.create" class="permission-name add-link" data-text="contentwarehouse.dataExportJobs.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  dataExportJobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.dataExportJobs.update" class="permission-name add-link" data-text="contentwarehouse.dataExportJobs.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  dataExportJobs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documentSchemas.create" class="permission-name add-link" data-text="contentwarehouse.documentSchemas.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documentSchemas.delete" class="permission-name add-link" data-text="contentwarehouse.documentSchemas.delete" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documentSchemas.get" class="permission-name add-link" data-text="contentwarehouse.documentSchemas.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documentSchemas.list" class="permission-name add-link" data-text="contentwarehouse.documentSchemas.list" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documentSchemas.update" class="permission-name add-link" data-text="contentwarehouse.documentSchemas.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documents.create" class="permission-name add-link" data-text="contentwarehouse.documents.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documents.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documents.delete" class="permission-name add-link" data-text="contentwarehouse.documents.delete" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documents.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documents.get" class="permission-name add-link" data-text="contentwarehouse.documents.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.documents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documents.getIamPolicy" class="permission-name add-link" data-text="contentwarehouse.documents.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documents.list" class="permission-name add-link" data-text="contentwarehouse.documents.list" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.documents.setIamPolicy" class="permission-name add-link" data-text="contentwarehouse.documents.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documents.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.documents.update" class="permission-name add-link" data-text="contentwarehouse.documents.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  documents.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.links.create" class="permission-name add-link" data-text="contentwarehouse.links.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.links.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.links.delete" class="permission-name add-link" data-text="contentwarehouse.links.delete" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.links.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.links.get" class="permission-name add-link" data-text="contentwarehouse.links.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.links.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.links.update" class="permission-name add-link" data-text="contentwarehouse.links.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.links.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.locations.getStatus" class="permission-name add-link" data-text="contentwarehouse.locations.getStatus" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  locations.  getStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.locations.initialize" class="permission-name add-link" data-text="contentwarehouse.locations.initialize" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  locations.  initialize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.operations.get" class="permission-name add-link" data-text="contentwarehouse.operations.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.rawDocuments.download" class="permission-name add-link" data-text="contentwarehouse.rawDocuments.download" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  download</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.rawDocuments.upload" class="permission-name add-link" data-text="contentwarehouse.rawDocuments.upload" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  rawDocuments.  upload</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.documentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.ruleSets.create" class="permission-name add-link" data-text="contentwarehouse.ruleSets.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  ruleSets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.ruleSets.delete" class="permission-name add-link" data-text="contentwarehouse.ruleSets.delete" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  ruleSets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.ruleSets.get" class="permission-name add-link" data-text="contentwarehouse.ruleSets.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.ruleSets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.ruleSets.list" class="permission-name add-link" data-text="contentwarehouse.ruleSets.list" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.ruleSets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.ruleSets.update" class="permission-name add-link" data-text="contentwarehouse.ruleSets.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  ruleSets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.synonymSets.create" class="permission-name add-link" data-text="contentwarehouse.synonymSets.create" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.synonymSets.delete" class="permission-name add-link" data-text="contentwarehouse.synonymSets.delete" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.synonymSets.get" class="permission-name add-link" data-text="contentwarehouse.synonymSets.get" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contentwarehouse.synonymSets.list" class="permission-name add-link" data-text="contentwarehouse.synonymSets.list" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contentwarehouse.synonymSets.update" class="permission-name add-link" data-text="contentwarehouse.synonymSets.update" tabindex="-1"><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.admin</code> )</p></td>
</tr>
</tbody>
</table>
