---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing
title: Commerce Agreement Publishing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Commerce Agreement Publishing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Commerce Agreement Publishing roles

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
<td><h4 id="commerceagreementpublishing.admin" class="role-title add-link" data-text="Commerce Agreement Publishing Admin Beta" tabindex="-1">Commerce Agreement Publishing Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p>Admin of Commerce Agreement Publishing service</p></td>
<td><p><code dir="ltr" translate="no">commerceagreementpublishing.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  create</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  delete</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  update</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  create</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  delete</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commerceagreementpublishing.viewer" class="role-title add-link" data-text="Commerce Agreement Publishing Viewer Beta" tabindex="-1">Commerce Agreement Publishing Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p>Viewer of Commerce Agreement Publishing service</p></td>
<td><p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  get</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  get</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Commerce Agreement Publishing permissions

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
<td><h4 id="commerceagreementpublishing.agreements.create" class="permission-name add-link" data-text="commerceagreementpublishing.agreements.create" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceagreementpublishing.agreements.delete" class="permission-name add-link" data-text="commerceagreementpublishing.agreements.delete" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceagreementpublishing.agreements.get" class="permission-name add-link" data-text="commerceagreementpublishing.agreements.get" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceagreementpublishing.agreements.list" class="permission-name add-link" data-text="commerceagreementpublishing.agreements.list" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceagreementpublishing.agreements.update" class="permission-name add-link" data-text="commerceagreementpublishing.agreements.update" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceagreementpublishing.documents.create" class="permission-name add-link" data-text="commerceagreementpublishing.documents.create" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceagreementpublishing.documents.delete" class="permission-name add-link" data-text="commerceagreementpublishing.documents.delete" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceagreementpublishing.documents.get" class="permission-name add-link" data-text="commerceagreementpublishing.documents.get" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceagreementpublishing.documents.list" class="permission-name add-link" data-text="commerceagreementpublishing.documents.list" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceagreementpublishing.documents.update" class="permission-name add-link" data-text="commerceagreementpublishing.documents.update" tabindex="-1"><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
</tbody>
</table>
