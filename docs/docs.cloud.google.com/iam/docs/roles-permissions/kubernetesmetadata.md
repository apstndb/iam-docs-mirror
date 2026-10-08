---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata
title: Kubernetes Metadata API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Kubernetes Metadata API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Kubernetes Metadata API roles

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
<td>Kubernetesmetadata Admin
<p>( <code>roles/ kubernetesmetadata.admin</code> )</p>
<p>Admin role for kubernetesmetadata</p></td>
<td><p><code>kubernetesmetadata.*</code></p>
<ul>
<li><code>kubernetesmetadata. metadata. config</code></li>
<li><code>kubernetesmetadata. metadata. publish</code></li>
<li><code>kubernetesmetadata. metadata. snapshot</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Kubernetesmetadata Viewer
<p>( <code>roles/ kubernetesmetadata.viewer</code> )</p>
<p>Viewer role for kubernetesmetadata</p></td>
<td><p><code>kubernetesmetadata. metadata. config</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Metadata Publisher
<p>( <code>roles/ kubernetesmetadata.publisher</code> )</p>
<p>Publisher of Kubernetes clusters metadata</p></td>
<td><p><code>kubernetesmetadata.*</code></p>
<ul>
<li><code>kubernetesmetadata. metadata. config</code></li>
<li><code>kubernetesmetadata. metadata. publish</code></li>
<li><code>kubernetesmetadata. metadata. snapshot</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Kubernetes Metadata API permissions

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
<td><code>kubernetesmetadata. metadata. config</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code>roles/ kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.viewer">Kubernetesmetadata Viewer</a> ( <code>roles/ kubernetesmetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.publisher">Metadata Publisher</a> ( <code>roles/ kubernetesmetadata.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>kubernetesmetadata. metadata. publish</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code>roles/ kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.publisher">Metadata Publisher</a> ( <code>roles/ kubernetesmetadata.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>kubernetesmetadata. metadata. snapshot</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code>roles/ kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.publisher">Metadata Publisher</a> ( <code>roles/ kubernetesmetadata.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
