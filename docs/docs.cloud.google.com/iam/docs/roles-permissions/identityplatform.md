---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/identityplatform
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform
title: Identity Platform roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Identity Platform. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Identity Platform roles

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
<td>Identity Platform Admin <sup>Beta</sup>
<p>( <code>roles/ identityplatform.admin</code> )</p>
<p>Full access to Identity Platform resources.</p></td>
<td><p><code>firebaseauth.*</code></p>
<ul>
<li><code>firebaseauth.configs.create</code></li>
<li><code>firebaseauth.configs.get</code></li>
<li><code>firebaseauth. configs. getHashConfig</code></li>
<li><code>firebaseauth.configs.getSecret</code></li>
<li><code>firebaseauth.configs.update</code></li>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>identitytoolkit.*</code></p>
<ul>
<li><code>identitytoolkit.tenants.create</code></li>
<li><code>identitytoolkit.tenants.delete</code></li>
<li><code>identitytoolkit.tenants.get</code></li>
<li><code>identitytoolkit. tenants. getIamPolicy</code></li>
<li><code>identitytoolkit.tenants.list</code></li>
<li><code>identitytoolkit. tenants. setIamPolicy</code></li>
<li><code>identitytoolkit.tenants.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Identity Platform Viewer <sup>Beta</sup>
<p>( <code>roles/ identityplatform.viewer</code> )</p>
<p>Read access to Identity Platform resources.</p></td>
<td><p><code>firebaseauth.configs.get</code></p>
<p><code>firebaseauth.users.get</code></p>
<p><code>identitytoolkit.tenants.get</code></p>
<p><code>identitytoolkit. tenants. getIamPolicy</code></p>
<p><code>identitytoolkit.tenants.list</code></p></td>
</tr>
</tbody>
</table>

## Identity Platform permissions

There are no IAM permissions for this service.
