---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement
title: Commerce Price Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Commerce Price Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Commerce Price Management roles

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
<td><h4 id="commercepricemanagement.editor" class="role-title add-link" data-text="Commercepricemanagement Editor Beta" tabindex="-1">Commercepricemanagement Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p>Editor role for commercepricemanagement</p></td>
<td><p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  get</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  get</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></p>
<p><code dir="ltr" translate="no">commerceprice.privateoffers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  cancel</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  create</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  delete</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  get</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  list</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  publish</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  sendEmail</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  get</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.  get</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.skuGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.skuGroups.get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  skuGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.skus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.skus.get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.skus.list</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.  standardOffers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.  standardOffers.  get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  standardOffers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commercepricemanagement.viewer" class="role-title add-link" data-text="Commerce Price Management Viewer Beta" tabindex="-1">Commerce Price Management Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p>Allows viewing offers, free trials, skus</p></td>
<td><p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  get</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  get</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></p>
<p><code dir="ltr" translate="no">commerceprice.  privateoffers.  get</code></p>
<p><code dir="ltr" translate="no">commerceprice.  privateoffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  get</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.  get</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.skuGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.skuGroups.get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  skuGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.skus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.skus.get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.skus.list</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.  standardOffers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.  standardOffers.  get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  standardOffers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="commercepricemanagement.eventsViewer" class="role-title add-link" data-text="Commerce Price Management Events Viewer Beta" tabindex="-1">Commerce Price Management Events Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercepricemanagement.eventsViewer</code> )</p>
<p>Allows viewing key events for an offer</p></td>
<td><p><code dir="ltr" translate="no">commerceprice.events.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceprice.events.get</code></li>
<li><code dir="ltr" translate="no">commerceprice.events.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="commercepricemanagement.privateOffersAdmin" class="role-title add-link" data-text="Commerce Price Management Private Offers Admin Beta" tabindex="-1">Commerce Price Management Private Offers Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p>Allows managing private offers</p></td>
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
<p><code dir="ltr" translate="no">commerceprice.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceprice.events.get</code></li>
<li><code dir="ltr" translate="no">commerceprice.events.list</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  cancel</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  create</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  delete</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  get</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  list</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  publish</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  sendEmail</code></li>
<li><code dir="ltr" translate="no">commerceprice.  privateoffers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  create</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  delete</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  list</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  cancel</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  create</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  delete</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  list</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  publish</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  privateOffers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.skuGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.skuGroups.get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  skuGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.skus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.skus.get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.skus.list</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceproducer.  standardOffers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceproducer.  standardOffers.  get</code></li>
<li><code dir="ltr" translate="no">commerceproducer.  standardOffers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Commerce Price Management permissions

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
<td><h4 id="commerceprice.events.get" class="permission-name add-link" data-text="commerceprice.events.get" tabindex="-1"><code dir="ltr" translate="no">commerceprice.events.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer">Commerce Price Management Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceprice.events.list" class="permission-name add-link" data-text="commerceprice.events.list" tabindex="-1"><code dir="ltr" translate="no">commerceprice.events.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer">Commerce Price Management Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceprice.privateoffers.cancel" class="permission-name add-link" data-text="commerceprice.privateoffers.cancel" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceprice.privateoffers.create" class="permission-name add-link" data-text="commerceprice.privateoffers.create" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceprice.privateoffers.delete" class="permission-name add-link" data-text="commerceprice.privateoffers.delete" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceprice.privateoffers.get" class="permission-name add-link" data-text="commerceprice.privateoffers.get" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceprice.privateoffers.list" class="permission-name add-link" data-text="commerceprice.privateoffers.list" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceprice.privateoffers.publish" class="permission-name add-link" data-text="commerceprice.privateoffers.publish" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  publish</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="commerceprice.privateoffers.sendEmail" class="permission-name add-link" data-text="commerceprice.privateoffers.sendEmail" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  sendEmail</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="commerceprice.privateoffers.update" class="permission-name add-link" data-text="commerceprice.privateoffers.update" tabindex="-1"><code dir="ltr" translate="no">commerceprice.  privateoffers.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commercepricemanagement.privateOffersAdmin</code> )</p></td>
</tr>
</tbody>
</table>
