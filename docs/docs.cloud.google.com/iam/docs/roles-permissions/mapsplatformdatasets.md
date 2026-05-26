---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets
title: Maps Platform Datasets roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Maps Platform Datasets. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Maps Platform Datasets roles

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
<td><h4 id="mapsplatformdatasets.admin" class="role-title add-link" data-text="Maps Platform Datasets Admin Beta" tabindex="-1">Maps Platform Datasets Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p>Grants read and write access to all the Maps Platform Datasets API resources</p></td>
<td><p><code dir="ltr" translate="no">mapsadmin.clientStyles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.create</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.delete</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.get</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">mapsplatformdatasets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  create</code></li>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  delete</code></li>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  export</code></li>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  get</code></li>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  import</code></li>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  list</code></li>
<li><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="mapsplatformdatasets.viewer" class="role-title add-link" data-text="Maps Platform Datasets Viewer Beta" tabindex="-1">Maps Platform Datasets Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p>Grants read-only access to all the Maps Platform Datasets API resources</p></td>
<td><p><code dir="ltr" translate="no">mapsadmin.clientStyles.get</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></p>
<p><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  export</code></p>
<p><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  get</code></p>
<p><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Maps Platform Datasets permissions

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
<td><h4 id="mapsplatformdatasets.datasets.create" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.create" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsplatformdatasets.datasets.delete" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsplatformdatasets.datasets.export" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.export" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsplatformdatasets.datasets.get" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.get" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsplatformdatasets.datasets.import" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.import" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsplatformdatasets.datasets.list" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.list" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsplatformdatasets.datasets.update" class="permission-name add-link" data-text="mapsplatformdatasets.datasets.update" tabindex="-1"><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
</tbody>
</table>
