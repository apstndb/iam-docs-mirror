---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking
title: Subscription Linking roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Subscription Linking. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Subscription Linking roles

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
<td><h4 id="readerrevenuesubscriptionlinking.admin" class="role-title add-link" data-text="Subscription Linking Admin" tabindex="-1">Subscription Linking Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p>
<p>Full access to publication reader resources</p></td>
<td><p><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.*</code></p>
<ul>
<li><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readerEntitlements.  get</code></li>
<li><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readerEntitlements.  update</code></li>
<li><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readers.  delete</code></li>
<li><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="readerrevenuesubscriptionlinking.viewer" class="role-title add-link" data-text="Subscription Linking Viewer" tabindex="-1">Subscription Linking Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.viewer</code> )</p>
<p>This role can view all publication reader resources</p></td>
<td><p><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readerEntitlements.  get</code></p>
<p><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readers.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="readerrevenuesubscriptionlinking.entitlementsViewer" class="role-title add-link" data-text="Subscription Linking Entitlements Viewer" tabindex="-1">Subscription Linking Entitlements Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.entitlementsViewer</code> )</p>
<p>This role can view all publication reader entitlements</p></td>
<td><p><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readerEntitlements.  get</code></p></td>
</tr>
</tbody>
</table>

## Subscription Linking permissions

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
<td><h4 id="readerrevenuesubscriptionlinking.readerEntitlements.get" class="permission-name add-link" data-text="readerrevenuesubscriptionlinking.readerEntitlements.get" tabindex="-1"><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readerEntitlements.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer">Subscription Linking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.entitlementsViewer">Subscription Linking Entitlements Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.entitlementsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="readerrevenuesubscriptionlinking.readerEntitlements.update" class="permission-name add-link" data-text="readerrevenuesubscriptionlinking.readerEntitlements.update" tabindex="-1"><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readerEntitlements.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="readerrevenuesubscriptionlinking.readers.delete" class="permission-name add-link" data-text="readerrevenuesubscriptionlinking.readers.delete" tabindex="-1"><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="readerrevenuesubscriptionlinking.readers.get" class="permission-name add-link" data-text="readerrevenuesubscriptionlinking.readers.get" tabindex="-1"><code dir="ltr" translate="no">readerrevenuesubscriptionlinking.  readers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer">Subscription Linking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  readerrevenuesubscriptionlinking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
