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
<td>Vector Search Admin
<p>( <code>roles/ vectorsearch.admin</code> )</p>
<p>Grants full access to all vectorsearch resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vectorsearch.*</code></p>
<ul>
<li><code>vectorsearch. collections. create</code></li>
<li><code>vectorsearch. collections. delete</code></li>
<li><code>vectorsearch.collections.get</code></li>
<li><code>vectorsearch.collections.list</code></li>
<li><code>vectorsearch. collections. update</code></li>
<li><code>vectorsearch. dataObjects. create</code></li>
<li><code>vectorsearch. dataObjects. delete</code></li>
<li><code>vectorsearch. dataObjects. export</code></li>
<li><code>vectorsearch.dataObjects.get</code></li>
<li><code>vectorsearch. dataObjects. import</code></li>
<li><code>vectorsearch.dataObjects.query</code></li>
<li><code>vectorsearch. dataObjects. search</code></li>
<li><code>vectorsearch. dataObjects. update</code></li>
<li><code>vectorsearch.indexes.create</code></li>
<li><code>vectorsearch.indexes.delete</code></li>
<li><code>vectorsearch.indexes.get</code></li>
<li><code>vectorsearch.indexes.list</code></li>
<li><code>vectorsearch.indexes.update</code></li>
<li><code>vectorsearch.locations.get</code></li>
<li><code>vectorsearch.locations.list</code></li>
<li><code>vectorsearch.operations.cancel</code></li>
<li><code>vectorsearch.operations.delete</code></li>
<li><code>vectorsearch.operations.get</code></li>
<li><code>vectorsearch.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Vector Search Viewer
<p>( <code>roles/ vectorsearch.viewer</code> )</p>
<p>Grants read access to all vectorsearch resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vectorsearch.collections.get</code></p>
<p><code>vectorsearch.collections.list</code></p>
<p><code>vectorsearch. dataObjects. export</code></p>
<p><code>vectorsearch.dataObjects.get</code></p>
<p><code>vectorsearch.dataObjects.query</code></p>
<p><code>vectorsearch. dataObjects. search</code></p>
<p><code>vectorsearch.indexes.get</code></p>
<p><code>vectorsearch.indexes.list</code></p>
<p><code>vectorsearch.locations.*</code></p>
<ul>
<li><code>vectorsearch.locations.get</code></li>
<li><code>vectorsearch.locations.list</code></li>
</ul>
<p><code>vectorsearch.operations.get</code></p>
<p><code>vectorsearch.operations.list</code></p></td>
</tr>
<tr class="odd">
<td>Vector Search Collection Writer
<p>( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p>Grants read-write access to Collections.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vectorsearch.collections.*</code></p>
<ul>
<li><code>vectorsearch. collections. create</code></li>
<li><code>vectorsearch. collections. delete</code></li>
<li><code>vectorsearch.collections.get</code></li>
<li><code>vectorsearch.collections.list</code></li>
<li><code>vectorsearch. collections. update</code></li>
</ul>
<p><code>vectorsearch.locations.*</code></p>
<ul>
<li><code>vectorsearch.locations.get</code></li>
<li><code>vectorsearch.locations.list</code></li>
</ul>
<p><code>vectorsearch.operations.*</code></p>
<ul>
<li><code>vectorsearch.operations.cancel</code></li>
<li><code>vectorsearch.operations.delete</code></li>
<li><code>vectorsearch.operations.get</code></li>
<li><code>vectorsearch.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Vector Search DataObject Writer
<p>( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p>Grants read-write access to DataObjects and read access to parent Collections.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vectorsearch.collections.get</code></p>
<p><code>vectorsearch.collections.list</code></p>
<p><code>vectorsearch.dataObjects.*</code></p>
<ul>
<li><code>vectorsearch. dataObjects. create</code></li>
<li><code>vectorsearch. dataObjects. delete</code></li>
<li><code>vectorsearch. dataObjects. export</code></li>
<li><code>vectorsearch.dataObjects.get</code></li>
<li><code>vectorsearch. dataObjects. import</code></li>
<li><code>vectorsearch.dataObjects.query</code></li>
<li><code>vectorsearch. dataObjects. search</code></li>
<li><code>vectorsearch. dataObjects. update</code></li>
</ul>
<p><code>vectorsearch.locations.*</code></p>
<ul>
<li><code>vectorsearch.locations.get</code></li>
<li><code>vectorsearch.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Vector Search Index Writer
<p>( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p>Grants read-write access to Indexes and read access to parent Collections.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vectorsearch.collections.get</code></p>
<p><code>vectorsearch.collections.list</code></p>
<p><code>vectorsearch.indexes.*</code></p>
<ul>
<li><code>vectorsearch.indexes.create</code></li>
<li><code>vectorsearch.indexes.delete</code></li>
<li><code>vectorsearch.indexes.get</code></li>
<li><code>vectorsearch.indexes.list</code></li>
<li><code>vectorsearch.indexes.update</code></li>
</ul>
<p><code>vectorsearch.locations.*</code></p>
<ul>
<li><code>vectorsearch.locations.get</code></li>
<li><code>vectorsearch.locations.list</code></li>
</ul>
<p><code>vectorsearch.operations.*</code></p>
<ul>
<li><code>vectorsearch.operations.cancel</code></li>
<li><code>vectorsearch.operations.delete</code></li>
<li><code>vectorsearch.operations.get</code></li>
<li><code>vectorsearch.operations.list</code></li>
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
<td>Vector Search Service Agent
<p>( <code>roles/ vectorsearch.serviceAgent</code> )</p>
<p>Gives Vector Search access to read Cloud Storage buckets, read/create objects, use Vertex Models, and call Discovery Engine RankService.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform. batchPredictionJobs. create</code></p>
<p><code>aiplatform. batchPredictionJobs. get</code></p>
<p><code>aiplatform.endpoints.predict</code></p>
<p><code>discoveryengine. rankingConfigs. rank</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>vectorsearch. collections. create</code></p>
<p><code>vectorsearch. collections. delete</code></p>
<p><code>vectorsearch. dataObjects. create</code></p>
<p><code>vectorsearch. dataObjects. delete</code></p>
<p><code>vectorsearch. dataObjects. import</code></p>
<p><code>vectorsearch. dataObjects. update</code></p>
<p><code>vectorsearch.indexes.delete</code></p></td>
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
<td><code>vectorsearch. collections. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch. collections. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.collections.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch.collections.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch. collections. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch. dataObjects. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch. dataObjects. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch. dataObjects. export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.dataObjects.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch. dataObjects. import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.dataObjects.query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch. dataObjects. search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch. dataObjects. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch.indexes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.indexes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a> ( <code>roles/ vectorsearch.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch.indexes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.indexes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch.indexes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vectorsearch.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vectorsearch.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vectorsearch.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vectorsearch.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a> ( <code>roles/ aiplatform.ragServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
