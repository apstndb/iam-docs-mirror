---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog
title: Commerce Offer Catalog roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Commerce Offer Catalog. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Commerce Offer Catalog roles

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
<td><h4 id="commerceoffercatalog.admin" class="role-title add-link" data-text="Commerce Offer Catalog Admin Beta" tabindex="-1">Commerce Offer Catalog Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p>Admin role for Commerce Offer Catalog</p></td>
<td><p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commerceoffercatalog.offersViewer" class="role-title add-link" data-text="Commerce Offer Catalog Offers Viewer Beta" tabindex="-1">Commerce Offer Catalog Offers Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commerceoffercatalog.offersViewer</code> )</p>
<p>Allows viewing offers</p></td>
<td><p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Commerce Offer Catalog permissions

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
<td><h4 id="commerceoffercatalog.agreements.get" class="permission-name add-link" data-text="commerceoffercatalog.agreements.get" tabindex="-1"><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.offersViewer">Commerce Offer Catalog Offers Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.offersViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceoffercatalog.agreements.list" class="permission-name add-link" data-text="commerceoffercatalog.agreements.list" tabindex="-1"><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.offersViewer">Commerce Offer Catalog Offers Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.offersViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceoffercatalog.documents.get" class="permission-name add-link" data-text="commerceoffercatalog.documents.get" tabindex="-1"><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.offersViewer">Commerce Offer Catalog Offers Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.offersViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceoffercatalog.documents.list" class="permission-name add-link" data-text="commerceoffercatalog.documents.list" tabindex="-1"><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.offersViewer">Commerce Offer Catalog Offers Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.offersViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceoffercatalog.offers.get" class="permission-name add-link" data-text="commerceoffercatalog.offers.get" tabindex="-1"><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.offersViewer">Commerce Offer Catalog Offers Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceoffercatalog.offersViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
