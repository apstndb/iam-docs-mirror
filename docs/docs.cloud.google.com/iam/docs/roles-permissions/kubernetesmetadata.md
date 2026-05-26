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
<td><h4 id="kubernetesmetadata.admin" class="role-title add-link" data-text="Kubernetesmetadata Admin" tabindex="-1">Kubernetesmetadata Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  kubernetesmetadata.admin</code> )</p>
<p>Admin role for kubernetesmetadata</p></td>
<td><p><code dir="ltr" translate="no">kubernetesmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  publish</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  snapshot</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="kubernetesmetadata.viewer" class="role-title add-link" data-text="Kubernetesmetadata Viewer" tabindex="-1">Kubernetesmetadata Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  kubernetesmetadata.viewer</code> )</p>
<p>Viewer role for kubernetesmetadata</p></td>
<td><p><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="kubernetesmetadata.publisher" class="role-title add-link" data-text="Metadata Publisher" tabindex="-1">Metadata Publisher</h4>
<p>( <code dir="ltr" translate="no">roles/  kubernetesmetadata.publisher</code> )</p>
<p>Publisher of Kubernetes clusters metadata</p></td>
<td><p><code dir="ltr" translate="no">kubernetesmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  publish</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  snapshot</code></li>
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
<td><h4 id="kubernetesmetadata.metadata.config" class="permission-name add-link" data-text="kubernetesmetadata.metadata.config" tabindex="-1"><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.viewer">Kubernetesmetadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.publisher">Metadata Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="kubernetesmetadata.metadata.publish" class="permission-name add-link" data-text="kubernetesmetadata.metadata.publish" tabindex="-1"><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  publish</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.publisher">Metadata Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="kubernetesmetadata.metadata.snapshot" class="permission-name add-link" data-text="kubernetesmetadata.metadata.snapshot" tabindex="-1"><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  snapshot</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.publisher">Metadata Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  kubernetesmetadata.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
