---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager
title: Certificate Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Certificate Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Certificate Manager roles

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
<td>Certificatemanager Admin
<p>( <code>roles/ certificatemanager.admin</code> )</p>
<p>Admin role for certificatemanager</p></td>
<td><p><code>certificatemanager.*</code></p>
<ul>
<li><code>certificatemanager. certissuanceconfigs. create</code></li>
<li><code>certificatemanager. certissuanceconfigs. createTagBinding</code></li>
<li><code>certificatemanager. certissuanceconfigs. delete</code></li>
<li><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></li>
<li><code>certificatemanager. certissuanceconfigs. get</code></li>
<li><code>certificatemanager. certissuanceconfigs. list</code></li>
<li><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></li>
<li><code>certificatemanager. certissuanceconfigs. listTagBindings</code></li>
<li><code>certificatemanager. certissuanceconfigs. update</code></li>
<li><code>certificatemanager. certissuanceconfigs. use</code></li>
<li><code>certificatemanager. certmapentries. create</code></li>
<li><code>certificatemanager. certmapentries. createTagBinding</code></li>
<li><code>certificatemanager. certmapentries. delete</code></li>
<li><code>certificatemanager. certmapentries. deleteTagBinding</code></li>
<li><code>certificatemanager. certmapentries. get</code></li>
<li><code>certificatemanager. certmapentries. list</code></li>
<li><code>certificatemanager. certmapentries. listEffectiveTags</code></li>
<li><code>certificatemanager. certmapentries. listTagBindings</code></li>
<li><code>certificatemanager. certmapentries. update</code></li>
<li><code>certificatemanager. certmaps. create</code></li>
<li><code>certificatemanager. certmaps. createTagBinding</code></li>
<li><code>certificatemanager. certmaps. delete</code></li>
<li><code>certificatemanager. certmaps. deleteTagBinding</code></li>
<li><code>certificatemanager. certmaps. get</code></li>
<li><code>certificatemanager. certmaps. list</code></li>
<li><code>certificatemanager. certmaps. listEffectiveTags</code></li>
<li><code>certificatemanager. certmaps. listTagBindings</code></li>
<li><code>certificatemanager. certmaps. update</code></li>
<li><code>certificatemanager. certmaps. use</code></li>
<li><code>certificatemanager. certs. create</code></li>
<li><code>certificatemanager. certs. createTagBinding</code></li>
<li><code>certificatemanager. certs. delete</code></li>
<li><code>certificatemanager. certs. deleteTagBinding</code></li>
<li><code>certificatemanager.certs.get</code></li>
<li><code>certificatemanager.certs.list</code></li>
<li><code>certificatemanager. certs. listEffectiveTags</code></li>
<li><code>certificatemanager. certs. listTagBindings</code></li>
<li><code>certificatemanager. certs. update</code></li>
<li><code>certificatemanager.certs.use</code></li>
<li><code>certificatemanager. dnsauthorizations. create</code></li>
<li><code>certificatemanager. dnsauthorizations. createTagBinding</code></li>
<li><code>certificatemanager. dnsauthorizations. delete</code></li>
<li><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></li>
<li><code>certificatemanager. dnsauthorizations. get</code></li>
<li><code>certificatemanager. dnsauthorizations. list</code></li>
<li><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></li>
<li><code>certificatemanager. dnsauthorizations. listTagBindings</code></li>
<li><code>certificatemanager. dnsauthorizations. update</code></li>
<li><code>certificatemanager. dnsauthorizations. use</code></li>
<li><code>certificatemanager. locations. get</code></li>
<li><code>certificatemanager. locations. list</code></li>
<li><code>certificatemanager. observedcerts. get</code></li>
<li><code>certificatemanager. observedcerts. list</code></li>
<li><code>certificatemanager. operations. cancel</code></li>
<li><code>certificatemanager. operations. delete</code></li>
<li><code>certificatemanager. operations. get</code></li>
<li><code>certificatemanager. operations. list</code></li>
<li><code>certificatemanager. trustconfigs. create</code></li>
<li><code>certificatemanager. trustconfigs. createTagBinding</code></li>
<li><code>certificatemanager. trustconfigs. delete</code></li>
<li><code>certificatemanager. trustconfigs. deleteTagBinding</code></li>
<li><code>certificatemanager. trustconfigs. get</code></li>
<li><code>certificatemanager. trustconfigs. list</code></li>
<li><code>certificatemanager. trustconfigs. listEffectiveTags</code></li>
<li><code>certificatemanager. trustconfigs. listTagBindings</code></li>
<li><code>certificatemanager. trustconfigs. update</code></li>
<li><code>certificatemanager. trustconfigs. use</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Certificate Manager Editor
<p>( <code>roles/ certificatemanager.editor</code> )</p>
<p>Edit access to Certificate Manager all resources.</p></td>
<td><p><code>certificatemanager. certissuanceconfigs. create</code></p>
<p><code>certificatemanager. certissuanceconfigs. createTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. get</code></p>
<p><code>certificatemanager. certissuanceconfigs. list</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certissuanceconfigs. update</code></p>
<p><code>certificatemanager. certissuanceconfigs. use</code></p>
<p><code>certificatemanager. certmapentries. create</code></p>
<p><code>certificatemanager. certmapentries. createTagBinding</code></p>
<p><code>certificatemanager. certmapentries. deleteTagBinding</code></p>
<p><code>certificatemanager. certmapentries. get</code></p>
<p><code>certificatemanager. certmapentries. list</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. update</code></p>
<p><code>certificatemanager. certmaps. create</code></p>
<p><code>certificatemanager. certmaps. createTagBinding</code></p>
<p><code>certificatemanager. certmaps. deleteTagBinding</code></p>
<p><code>certificatemanager. certmaps. get</code></p>
<p><code>certificatemanager. certmaps. list</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. update</code></p>
<p><code>certificatemanager. certmaps. use</code></p>
<p><code>certificatemanager. certs. create</code></p>
<p><code>certificatemanager. certs. createTagBinding</code></p>
<p><code>certificatemanager. certs. deleteTagBinding</code></p>
<p><code>certificatemanager.certs.get</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. certs. update</code></p>
<p><code>certificatemanager.certs.use</code></p>
<p><code>certificatemanager. dnsauthorizations. create</code></p>
<p><code>certificatemanager. dnsauthorizations. createTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. get</code></p>
<p><code>certificatemanager. dnsauthorizations. list</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. update</code></p>
<p><code>certificatemanager. dnsauthorizations. use</code></p>
<p><code>certificatemanager.locations.*</code></p>
<ul>
<li><code>certificatemanager. locations. get</code></li>
<li><code>certificatemanager. locations. list</code></li>
</ul>
<p><code>certificatemanager. observedcerts.*</code></p>
<ul>
<li><code>certificatemanager. observedcerts. get</code></li>
<li><code>certificatemanager. observedcerts. list</code></li>
</ul>
<p><code>certificatemanager. operations. get</code></p>
<p><code>certificatemanager. operations. list</code></p>
<p><code>certificatemanager. trustconfigs. create</code></p>
<p><code>certificatemanager. trustconfigs. createTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. get</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>certificatemanager. trustconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. trustconfigs. listTagBindings</code></p>
<p><code>certificatemanager. trustconfigs. update</code></p>
<p><code>certificatemanager. trustconfigs. use</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Certificate Manager Viewer
<p>( <code>roles/ certificatemanager.viewer</code> )</p>
<p>Read-only access to Certificate Manager all resources.</p></td>
<td><p><code>certificatemanager. certissuanceconfigs. get</code></p>
<p><code>certificatemanager. certissuanceconfigs. list</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. get</code></p>
<p><code>certificatemanager. certmapentries. list</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. get</code></p>
<p><code>certificatemanager. certmaps. list</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager.certs.get</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. get</code></p>
<p><code>certificatemanager. dnsauthorizations. list</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager.locations.*</code></p>
<ul>
<li><code>certificatemanager. locations. get</code></li>
<li><code>certificatemanager. locations. list</code></li>
</ul>
<p><code>certificatemanager. observedcerts.*</code></p>
<ul>
<li><code>certificatemanager. observedcerts. get</code></li>
<li><code>certificatemanager. observedcerts. list</code></li>
</ul>
<p><code>certificatemanager. operations. get</code></p>
<p><code>certificatemanager. operations. list</code></p>
<p><code>certificatemanager. trustconfigs. get</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>certificatemanager. trustconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. trustconfigs. listTagBindings</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Certificate Manager Owner
<p>( <code>roles/ certificatemanager.owner</code> )</p>
<p>Full access to Certificate Manager all resources.</p></td>
<td><p><code>certificatemanager.*</code></p>
<ul>
<li><code>certificatemanager. certissuanceconfigs. create</code></li>
<li><code>certificatemanager. certissuanceconfigs. createTagBinding</code></li>
<li><code>certificatemanager. certissuanceconfigs. delete</code></li>
<li><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></li>
<li><code>certificatemanager. certissuanceconfigs. get</code></li>
<li><code>certificatemanager. certissuanceconfigs. list</code></li>
<li><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></li>
<li><code>certificatemanager. certissuanceconfigs. listTagBindings</code></li>
<li><code>certificatemanager. certissuanceconfigs. update</code></li>
<li><code>certificatemanager. certissuanceconfigs. use</code></li>
<li><code>certificatemanager. certmapentries. create</code></li>
<li><code>certificatemanager. certmapentries. createTagBinding</code></li>
<li><code>certificatemanager. certmapentries. delete</code></li>
<li><code>certificatemanager. certmapentries. deleteTagBinding</code></li>
<li><code>certificatemanager. certmapentries. get</code></li>
<li><code>certificatemanager. certmapentries. list</code></li>
<li><code>certificatemanager. certmapentries. listEffectiveTags</code></li>
<li><code>certificatemanager. certmapentries. listTagBindings</code></li>
<li><code>certificatemanager. certmapentries. update</code></li>
<li><code>certificatemanager. certmaps. create</code></li>
<li><code>certificatemanager. certmaps. createTagBinding</code></li>
<li><code>certificatemanager. certmaps. delete</code></li>
<li><code>certificatemanager. certmaps. deleteTagBinding</code></li>
<li><code>certificatemanager. certmaps. get</code></li>
<li><code>certificatemanager. certmaps. list</code></li>
<li><code>certificatemanager. certmaps. listEffectiveTags</code></li>
<li><code>certificatemanager. certmaps. listTagBindings</code></li>
<li><code>certificatemanager. certmaps. update</code></li>
<li><code>certificatemanager. certmaps. use</code></li>
<li><code>certificatemanager. certs. create</code></li>
<li><code>certificatemanager. certs. createTagBinding</code></li>
<li><code>certificatemanager. certs. delete</code></li>
<li><code>certificatemanager. certs. deleteTagBinding</code></li>
<li><code>certificatemanager.certs.get</code></li>
<li><code>certificatemanager.certs.list</code></li>
<li><code>certificatemanager. certs. listEffectiveTags</code></li>
<li><code>certificatemanager. certs. listTagBindings</code></li>
<li><code>certificatemanager. certs. update</code></li>
<li><code>certificatemanager.certs.use</code></li>
<li><code>certificatemanager. dnsauthorizations. create</code></li>
<li><code>certificatemanager. dnsauthorizations. createTagBinding</code></li>
<li><code>certificatemanager. dnsauthorizations. delete</code></li>
<li><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></li>
<li><code>certificatemanager. dnsauthorizations. get</code></li>
<li><code>certificatemanager. dnsauthorizations. list</code></li>
<li><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></li>
<li><code>certificatemanager. dnsauthorizations. listTagBindings</code></li>
<li><code>certificatemanager. dnsauthorizations. update</code></li>
<li><code>certificatemanager. dnsauthorizations. use</code></li>
<li><code>certificatemanager. locations. get</code></li>
<li><code>certificatemanager. locations. list</code></li>
<li><code>certificatemanager. observedcerts. get</code></li>
<li><code>certificatemanager. observedcerts. list</code></li>
<li><code>certificatemanager. operations. cancel</code></li>
<li><code>certificatemanager. operations. delete</code></li>
<li><code>certificatemanager. operations. get</code></li>
<li><code>certificatemanager. operations. list</code></li>
<li><code>certificatemanager. trustconfigs. create</code></li>
<li><code>certificatemanager. trustconfigs. createTagBinding</code></li>
<li><code>certificatemanager. trustconfigs. delete</code></li>
<li><code>certificatemanager. trustconfigs. deleteTagBinding</code></li>
<li><code>certificatemanager. trustconfigs. get</code></li>
<li><code>certificatemanager. trustconfigs. list</code></li>
<li><code>certificatemanager. trustconfigs. listEffectiveTags</code></li>
<li><code>certificatemanager. trustconfigs. listTagBindings</code></li>
<li><code>certificatemanager. trustconfigs. update</code></li>
<li><code>certificatemanager. trustconfigs. use</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Certificate Manager Service Agent
<p>( <code>roles/ certificatemanager.serviceAgent</code> )</p>
<p>Grants Certificate Manager access to services and APIs in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>certificatemanager. locations. get</code></p></td>
</tr>
</tbody>
</table>

## Certificate Manager permissions

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
<td><code>certificatemanager. certissuanceconfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certissuanceconfigs. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certissuanceconfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certissuanceconfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certissuanceconfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certissuanceconfigs. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certissuanceconfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certissuanceconfigs. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmapentries. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmapentries. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmapentries. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmapentries. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmapentries. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmapentries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmapentries. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmapentries. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmapentries. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmaps. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmaps. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmaps. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmaps. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmaps. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmaps. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmaps. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmaps. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certmaps. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certmaps. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certs. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certs. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager.certs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager.certs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certs. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. certs. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. certs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager.certs.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. dnsauthorizations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. dnsauthorizations. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. dnsauthorizations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. dnsauthorizations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. dnsauthorizations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. dnsauthorizations. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. dnsauthorizations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. dnsauthorizations. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.serviceAgent">Certificate Manager Service Agent</a> ( <code>roles/ certificatemanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. observedcerts. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. observedcerts. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. trustconfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. trustconfigs. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. trustconfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. trustconfigs. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>certificatemanager. trustconfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. trustconfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. trustconfigs. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. trustconfigs. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>certificatemanager. trustconfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>certificatemanager. trustconfigs. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
