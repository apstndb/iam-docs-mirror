---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/publicca
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/publicca
title: Public Certificate Authority roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Public Certificate Authority. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Public Certificate Authority roles

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
<td><h4 id="publicca.admin" class="role-title add-link" data-text="Publicca Admin Beta" tabindex="-1">Publicca Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  publicca.admin</code> )</p>
<p>Admin role for publicca</p></td>
<td><p><code dir="ltr" translate="no">publicca.  externalAccountKeys.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="publicca.externalAccountKeyCreator" class="role-title add-link" data-text="External Account Key Creator Beta" tabindex="-1">External Account Key Creator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  publicca.externalAccountKeyCreator</code> )</p>
<p>This role can create a new externalAccountKey resource.</p></td>
<td><p><code dir="ltr" translate="no">publicca.  externalAccountKeys.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Public Certificate Authority permissions

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
<td><h4 id="publicca.externalAccountKeys.create" class="permission-name add-link" data-text="publicca.externalAccountKeys.create" tabindex="-1"><code dir="ltr" translate="no">publicca.  externalAccountKeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.admin">Publicca Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  publicca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.externalAccountKeyCreator">External Account Key Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  publicca.externalAccountKeyCreator</code> )</p></td>
</tr>
</tbody>
</table>
