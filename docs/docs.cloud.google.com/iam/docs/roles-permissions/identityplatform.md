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
<td><h4 id="identityplatform.admin" class="role-title add-link" data-text="Identity Platform Admin Beta" tabindex="-1">Identity Platform Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p>Full access to Identity Platform resources.</p></td>
<td><p><code dir="ltr" translate="no">firebaseauth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.configs.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.update</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">identitytoolkit.*</code></p>
<ul>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.create</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.delete</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.  tenants.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="identityplatform.viewer" class="role-title add-link" data-text="Identity Platform Viewer Beta" tabindex="-1">Identity Platform Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  identityplatform.viewer</code> )</p>
<p>Read access to Identity Platform resources.</p></td>
<td><p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.users.get</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></p></td>
</tr>
</tbody>
</table>

## Identity Platform permissions

There are no IAM permissions for this service.
