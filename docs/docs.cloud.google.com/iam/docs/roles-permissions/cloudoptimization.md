---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization
title: Cloud Optimization roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Optimization. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Optimization roles

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
<td><h4 id="cloudoptimization.admin" class="role-title add-link" data-text="Cloud Optimization AI Admin" tabindex="-1">Cloud Optimization AI Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudoptimization.admin</code> )</p>
<p>Administrator of Cloud Optimization AI resources</p></td>
<td><p><code dir="ltr" translate="no">cloudoptimization.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudoptimization.  operations.  create</code></li>
<li><code dir="ltr" translate="no">cloudoptimization.  operations.  get</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudoptimization.editor" class="role-title add-link" data-text="Cloud Optimization AI Editor" tabindex="-1">Cloud Optimization AI Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudoptimization.editor</code> )</p>
<p>Editor of Cloud Optimization AI resources</p></td>
<td><p><code dir="ltr" translate="no">cloudoptimization.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudoptimization.  operations.  create</code></li>
<li><code dir="ltr" translate="no">cloudoptimization.  operations.  get</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudoptimization.viewer" class="role-title add-link" data-text="Cloud Optimization AI Viewer" tabindex="-1">Cloud Optimization AI Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudoptimization.viewer</code> )</p>
<p>Viewer of Cloud Optimization AI resources</p></td>
<td><p><code dir="ltr" translate="no">cloudoptimization.  operations.  get</code></p></td>
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
<td><h4 id="cloudoptimization.serviceAgent" class="role-title add-link" data-text="Cloud Optimization Service Agent" tabindex="-1">Cloud Optimization Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudoptimization.serviceAgent</code> )</p>
<p>Grants Cloud Optimization Service Account access to read and write data in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Cloud Optimization permissions

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
<td><h4 id="cloudoptimization.operations.create" class="permission-name add-link" data-text="cloudoptimization.operations.create" tabindex="-1"><code dir="ltr" translate="no">cloudoptimization.  operations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.admin">Cloud Optimization AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.editor">Cloud Optimization AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudoptimization.operations.get" class="permission-name add-link" data-text="cloudoptimization.operations.get" tabindex="-1"><code dir="ltr" translate="no">cloudoptimization.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.admin">Cloud Optimization AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.editor">Cloud Optimization AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.viewer">Cloud Optimization AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudoptimization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
