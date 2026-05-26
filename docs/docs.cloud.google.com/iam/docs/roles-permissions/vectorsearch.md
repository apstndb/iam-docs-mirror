---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch
title: Vector Search roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Vector Search. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Vector Search roles

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
<td><h4 id="vectorsearch.admin" class="role-title add-link" data-text="Vector Search Admin" tabindex="-1">Vector Search Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p>Grants full access to all vectorsearch resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.  collections.  create</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  collections.  delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.collections.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.collections.list</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  collections.  update</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  create</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.dataObjects.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  import</code></li>
<li><code dir="ltr" translate="no">vectorsearch.dataObjects.query</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  search</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  update</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.create</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.list</code></li>
<li><code dir="ltr" translate="no">vectorsearch.locations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.locations.list</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.cancel</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.viewer" class="role-title add-link" data-text="Vector Search Viewer" tabindex="-1">Vector Search Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p>Grants read access to all vectorsearch resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.get</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.dataObjects.get</code></p>
<p><code dir="ltr" translate="no">vectorsearch.dataObjects.query</code></p>
<p><code dir="ltr" translate="no">vectorsearch.  dataObjects.  search</code></p>
<p><code dir="ltr" translate="no">vectorsearch.indexes.get</code></p>
<p><code dir="ltr" translate="no">vectorsearch.indexes.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.locations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vectorsearch.operations.get</code></p>
<p><code dir="ltr" translate="no">vectorsearch.operations.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.collectionWriter" class="role-title add-link" data-text="Vector Search Collection Writer" tabindex="-1">Vector Search Collection Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p>Grants read-write access to Collections.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.  collections.  create</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  collections.  delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.collections.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.collections.list</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  collections.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vectorsearch.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.locations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vectorsearch.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.operations.cancel</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.dataObjectWriter" class="role-title add-link" data-text="Vector Search DataObject Writer" tabindex="-1">Vector Search DataObject Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Grants read-write access to DataObjects and read access to parent Collections.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.get</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.dataObjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  create</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.dataObjects.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  import</code></li>
<li><code dir="ltr" translate="no">vectorsearch.dataObjects.query</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  search</code></li>
<li><code dir="ltr" translate="no">vectorsearch.  dataObjects.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vectorsearch.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.locations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.indexWriter" class="role-title add-link" data-text="Vector Search Index Writer" tabindex="-1">Vector Search Index Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Grants read-write access to Indexes and read access to parent Collections.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.get</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.indexes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.indexes.create</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.indexes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vectorsearch.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.locations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vectorsearch.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vectorsearch.operations.cancel</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.delete</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.get</code></li>
<li><code dir="ltr" translate="no">vectorsearch.operations.list</code></li>
</ul></td>
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
<td><h4 id="vectorsearch.serviceAgent" class="role-title add-link" data-text="Vector Search Service Agent" tabindex="-1">Vector Search Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  vectorsearch.serviceAgent</code> )</p>
<p>Gives Vector Search access to read Cloud Storage buckets and read/create objects.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.endpoints.predict</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Vector Search permissions

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
<td><h4 id="vectorsearch.collections.create" class="permission-name add-link" data-text="vectorsearch.collections.create" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  collections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.collections.delete" class="permission-name add-link" data-text="vectorsearch.collections.delete" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  collections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.collections.get" class="permission-name add-link" data-text="vectorsearch.collections.get" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.collections.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.collections.list" class="permission-name add-link" data-text="vectorsearch.collections.list" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.collections.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.collections.update" class="permission-name add-link" data-text="vectorsearch.collections.update" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  collections.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.dataObjects.create" class="permission-name add-link" data-text="vectorsearch.dataObjects.create" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  dataObjects.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.dataObjects.delete" class="permission-name add-link" data-text="vectorsearch.dataObjects.delete" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  dataObjects.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.dataObjects.get" class="permission-name add-link" data-text="vectorsearch.dataObjects.get" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.dataObjects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.dataObjects.import" class="permission-name add-link" data-text="vectorsearch.dataObjects.import" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  dataObjects.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.dataObjects.query" class="permission-name add-link" data-text="vectorsearch.dataObjects.query" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.dataObjects.query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.dataObjects.search" class="permission-name add-link" data-text="vectorsearch.dataObjects.search" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  dataObjects.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.dataObjects.update" class="permission-name add-link" data-text="vectorsearch.dataObjects.update" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.  dataObjects.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.indexes.create" class="permission-name add-link" data-text="vectorsearch.indexes.create" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.indexes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.indexes.delete" class="permission-name add-link" data-text="vectorsearch.indexes.delete" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.indexes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.indexes.get" class="permission-name add-link" data-text="vectorsearch.indexes.get" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.indexes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.indexes.list" class="permission-name add-link" data-text="vectorsearch.indexes.list" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.indexes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.locations.get" class="permission-name add-link" data-text="vectorsearch.locations.get" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.locations.list" class="permission-name add-link" data-text="vectorsearch.locations.list" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.operations.cancel" class="permission-name add-link" data-text="vectorsearch.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.operations.delete" class="permission-name add-link" data-text="vectorsearch.operations.delete" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vectorsearch.operations.get" class="permission-name add-link" data-text="vectorsearch.operations.get" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vectorsearch.operations.list" class="permission-name add-link" data-text="vectorsearch.operations.list" tabindex="-1"><code dir="ltr" translate="no">vectorsearch.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vectorsearch.indexWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
