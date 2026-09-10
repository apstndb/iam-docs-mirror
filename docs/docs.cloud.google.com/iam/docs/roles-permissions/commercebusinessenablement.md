---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement
title: Commerce Business Enablement roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Commerce Business Enablement. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Commerce Business Enablement roles

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
<td><h4 id="commercebusinessenablement.admin" class="role-title add-link" data-text="Commerce Business Enablement Configuration Admin Beta" tabindex="-1">Commerce Business Enablement Configuration Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p>Admin of Various Provider Configuration resources</p></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.update</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  leadgenConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  leadgenConfig.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  leadgenConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  list</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.viewer" class="role-title add-link" data-text="Commerce Business Enablement Configuration Viewer Beta" tabindex="-1">Commerce Business Enablement Configuration Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p>Viewer of Various Provider Configuration resource</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  leadgenConfig.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.paymentConfigAdmin" class="role-title add-link" data-text="Commerce Business Enablement PaymentConfig Admin Beta" tabindex="-1">Commerce Business Enablement PaymentConfig Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p>Administration of Payment Configuration resource</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  paymentConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  paymentConfig.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  paymentConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.paymentConfigViewer" class="role-title add-link" data-text="Commerce Business Enablement PaymentConfig Viewer Beta" tabindex="-1">Commerce Business Enablement PaymentConfig Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigViewer</code> )</p>
<p>Viewer of Payment Configuration resource</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  paymentConfig.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.rebatesAdmin" class="role-title add-link" data-text="Commerce Business Enablement Rebates Admin Beta" tabindex="-1">Commerce Business Enablement Rebates Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p>
<p>Provides admin access to rebates</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  refunds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  cancel</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  create</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  delete</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  list</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  start</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.rebatesViewer" class="role-title add-link" data-text="Commerce Business Enablement Rebates Viewer Beta" tabindex="-1">Commerce Business Enablement Rebates Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesViewer</code> )</p>
<p>Provides read-only access to rebates</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerDiscountAdmin" class="role-title add-link" data-text="Commerce Business Enablement Reseller Discount Admin Beta" tabindex="-1">Commerce Business Enablement Reseller Discount Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p>Provides admin access to reseller discount offers</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountConfig.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  cancel</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  create</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  cancel</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  create</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  delete</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  list</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  publish</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerDiscountViewer" class="role-title add-link" data-text="Commerce Business Enablement Reseller Discount Viewer Beta" tabindex="-1">Commerce Business Enablement Reseller Discount Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p>Provides read-only access to reseller discount offers</p></td>
<td><p><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  get</code></li>
<li><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountConfig.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  get</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Commerce Business Enablement permissions

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
<td><h4 id="commercebusinessenablement.leadgenConfig.get" class="permission-name add-link" data-text="commercebusinessenablement.leadgenConfig.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  leadgenConfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.leadgenConfig.update" class="permission-name add-link" data-text="commercebusinessenablement.leadgenConfig.update" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  leadgenConfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.operations.cancel" class="permission-name add-link" data-text="commercebusinessenablement.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.operations.delete" class="permission-name add-link" data-text="commercebusinessenablement.operations.delete" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.operations.get" class="permission-name add-link" data-text="commercebusinessenablement.operations.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesViewer">Commerce Business Enablement Rebates Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.operations.list" class="permission-name add-link" data-text="commercebusinessenablement.operations.list" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesViewer">Commerce Business Enablement Rebates Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.partnerAccounts.get" class="permission-name add-link" data-text="commercebusinessenablement.partnerAccounts.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.partnerAccounts.list" class="permission-name add-link" data-text="commercebusinessenablement.partnerAccounts.list" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.partnerInfo.get" class="permission-name add-link" data-text="commercebusinessenablement.partnerInfo.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  partnerInfo.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.admin">Commerce Producer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.viewer">Commerce Producer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigViewer">Commerce Business Enablement PaymentConfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesViewer">Commerce Business Enablement Rebates Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.paymentConfig.get" class="permission-name add-link" data-text="commercebusinessenablement.paymentConfig.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  paymentConfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigViewer">Commerce Business Enablement PaymentConfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.paymentConfig.update" class="permission-name add-link" data-text="commercebusinessenablement.paymentConfig.update" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  paymentConfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.paymentConfigAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.refunds.cancel" class="permission-name add-link" data-text="commercebusinessenablement.refunds.cancel" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.refunds.create" class="permission-name add-link" data-text="commercebusinessenablement.refunds.create" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.refunds.delete" class="permission-name add-link" data-text="commercebusinessenablement.refunds.delete" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.refunds.get" class="permission-name add-link" data-text="commercebusinessenablement.refunds.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesViewer">Commerce Business Enablement Rebates Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.refunds.list" class="permission-name add-link" data-text="commercebusinessenablement.refunds.list" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesViewer">Commerce Business Enablement Rebates Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.refunds.start" class="permission-name add-link" data-text="commercebusinessenablement.refunds.start" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.refunds.update" class="permission-name add-link" data-text="commercebusinessenablement.refunds.update" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.rebatesAdmin">Commerce Business Enablement Rebates Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.rebatesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerConfig.get" class="permission-name add-link" data-text="commercebusinessenablement.resellerConfig.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerConfig.update" class="permission-name add-link" data-text="commercebusinessenablement.resellerConfig.update" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerConfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerDiscountConfig.get" class="permission-name add-link" data-text="commercebusinessenablement.resellerDiscountConfig.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountConfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerDiscountOffers.cancel" class="permission-name add-link" data-text="commercebusinessenablement.resellerDiscountOffers.cancel" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerDiscountOffers.create" class="permission-name add-link" data-text="commercebusinessenablement.resellerDiscountOffers.create" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerDiscountOffers.list" class="permission-name add-link" data-text="commercebusinessenablement.resellerDiscountOffers.list" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.cancel" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.cancel" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.create" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.create" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.delete" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.delete" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.get" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.get" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.list" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.list" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.publish" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.publish" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  publish</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerPrivateOfferPlans.update" class="permission-name add-link" data-text="commercebusinessenablement.resellerPrivateOfferPlans.update" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.resellerDiscountAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commercebusinessenablement.resellerRestrictions.list" class="permission-name add-link" data-text="commercebusinessenablement.resellerRestrictions.list" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commercebusinessenablement.resellerRestrictions.update" class="permission-name add-link" data-text="commercebusinessenablement.resellerRestrictions.update" tabindex="-1"><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercebusinessenablement.admin</code> )</p></td>
</tr>
</tbody>
</table>
