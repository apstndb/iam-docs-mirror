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
<td>Commercepricemanagement Editor <sup>Beta</sup>
<p>( <code>roles/ commercepricemanagement.editor</code> )</p>
<p>Editor role for commercepricemanagement</p></td>
<td><p><code>commerceagreementpublishing. agreements. get</code></p>
<p><code>commerceagreementpublishing. agreements. list</code></p>
<p><code>commerceagreementpublishing. documents. get</code></p>
<p><code>commerceagreementpublishing. documents. list</code></p>
<p><code>commerceprice.privateoffers.*</code></p>
<ul>
<li><code>commerceprice. privateoffers. cancel</code></li>
<li><code>commerceprice. privateoffers. create</code></li>
<li><code>commerceprice. privateoffers. delete</code></li>
<li><code>commerceprice. privateoffers. get</code></li>
<li><code>commerceprice. privateoffers. list</code></li>
<li><code>commerceprice. privateoffers. publish</code></li>
<li><code>commerceprice. privateoffers. sendEmail</code></li>
<li><code>commerceprice. privateoffers. update</code></li>
</ul>
<p><code>commerceproducer. privateOfferDocuments. get</code></p>
<p><code>commerceproducer. privateOfferDocuments. list</code></p>
<p><code>commerceproducer. privateOffers. get</code></p>
<p><code>commerceproducer. privateOffers. list</code></p>
<p><code>commerceproducer.skuGroups.*</code></p>
<ul>
<li><code>commerceproducer.skuGroups.get</code></li>
<li><code>commerceproducer. skuGroups. list</code></li>
</ul>
<p><code>commerceproducer.skus.*</code></p>
<ul>
<li><code>commerceproducer.skus.get</code></li>
<li><code>commerceproducer.skus.list</code></li>
</ul>
<p><code>commerceproducer. standardOffers.*</code></p>
<ul>
<li><code>commerceproducer. standardOffers. get</code></li>
<li><code>commerceproducer. standardOffers. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Commerce Price Management Viewer <sup>Beta</sup>
<p>( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p>Allows viewing offers, free trials, skus</p></td>
<td><p><code>commerceagreementpublishing. agreements. get</code></p>
<p><code>commerceagreementpublishing. agreements. list</code></p>
<p><code>commerceagreementpublishing. documents. get</code></p>
<p><code>commerceagreementpublishing. documents. list</code></p>
<p><code>commerceprice. privateoffers. get</code></p>
<p><code>commerceprice. privateoffers. list</code></p>
<p><code>commerceproducer. privateOfferDocuments. get</code></p>
<p><code>commerceproducer. privateOfferDocuments. list</code></p>
<p><code>commerceproducer. privateOffers. get</code></p>
<p><code>commerceproducer. privateOffers. list</code></p>
<p><code>commerceproducer.skuGroups.*</code></p>
<ul>
<li><code>commerceproducer.skuGroups.get</code></li>
<li><code>commerceproducer. skuGroups. list</code></li>
</ul>
<p><code>commerceproducer.skus.*</code></p>
<ul>
<li><code>commerceproducer.skus.get</code></li>
<li><code>commerceproducer.skus.list</code></li>
</ul>
<p><code>commerceproducer. standardOffers.*</code></p>
<ul>
<li><code>commerceproducer. standardOffers. get</code></li>
<li><code>commerceproducer. standardOffers. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Commerce Price Management Events Viewer <sup>Beta</sup>
<p>( <code>roles/ commercepricemanagement.eventsViewer</code> )</p>
<p>Allows viewing key events for an offer</p></td>
<td><p><code>commerceprice.events.*</code></p>
<ul>
<li><code>commerceprice.events.get</code></li>
<li><code>commerceprice.events.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Commerce Price Management Private Offers Admin <sup>Beta</sup>
<p>( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p>Allows managing private offers</p></td>
<td><p><code>commerceagreementpublishing.*</code></p>
<ul>
<li><code>commerceagreementpublishing. agreements. create</code></li>
<li><code>commerceagreementpublishing. agreements. delete</code></li>
<li><code>commerceagreementpublishing. agreements. get</code></li>
<li><code>commerceagreementpublishing. agreements. list</code></li>
<li><code>commerceagreementpublishing. agreements. update</code></li>
<li><code>commerceagreementpublishing. documents. create</code></li>
<li><code>commerceagreementpublishing. documents. delete</code></li>
<li><code>commerceagreementpublishing. documents. get</code></li>
<li><code>commerceagreementpublishing. documents. list</code></li>
<li><code>commerceagreementpublishing. documents. update</code></li>
</ul>
<p><code>commerceprice.*</code></p>
<ul>
<li><code>commerceprice.events.get</code></li>
<li><code>commerceprice.events.list</code></li>
<li><code>commerceprice. privateoffers. cancel</code></li>
<li><code>commerceprice. privateoffers. create</code></li>
<li><code>commerceprice. privateoffers. delete</code></li>
<li><code>commerceprice. privateoffers. get</code></li>
<li><code>commerceprice. privateoffers. list</code></li>
<li><code>commerceprice. privateoffers. publish</code></li>
<li><code>commerceprice. privateoffers. sendEmail</code></li>
<li><code>commerceprice. privateoffers. update</code></li>
</ul>
<p><code>commerceproducer. privateOfferDocuments.*</code></p>
<ul>
<li><code>commerceproducer. privateOfferDocuments. create</code></li>
<li><code>commerceproducer. privateOfferDocuments. delete</code></li>
<li><code>commerceproducer. privateOfferDocuments. get</code></li>
<li><code>commerceproducer. privateOfferDocuments. list</code></li>
<li><code>commerceproducer. privateOfferDocuments. update</code></li>
</ul>
<p><code>commerceproducer. privateOffers.*</code></p>
<ul>
<li><code>commerceproducer. privateOffers. cancel</code></li>
<li><code>commerceproducer. privateOffers. create</code></li>
<li><code>commerceproducer. privateOffers. delete</code></li>
<li><code>commerceproducer. privateOffers. get</code></li>
<li><code>commerceproducer. privateOffers. list</code></li>
<li><code>commerceproducer. privateOffers. publish</code></li>
<li><code>commerceproducer. privateOffers. update</code></li>
</ul>
<p><code>commerceproducer.skuGroups.*</code></p>
<ul>
<li><code>commerceproducer.skuGroups.get</code></li>
<li><code>commerceproducer. skuGroups. list</code></li>
</ul>
<p><code>commerceproducer.skus.*</code></p>
<ul>
<li><code>commerceproducer.skus.get</code></li>
<li><code>commerceproducer.skus.list</code></li>
</ul>
<p><code>commerceproducer. standardOffers.*</code></p>
<ul>
<li><code>commerceproducer. standardOffers. get</code></li>
<li><code>commerceproducer. standardOffers. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Commerce Price Management permissions

| Permission                                | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `commerceprice.events.get`                | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Commerce Price Management Events Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer) ( `roles/ commercepricemanagement.eventsViewer` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `commerceprice.events.list`               | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Commerce Price Management Events Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer) ( `roles/ commercepricemanagement.eventsViewer` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `commerceprice. privateoffers. cancel`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `commerceprice. privateoffers. create`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `commerceprice. privateoffers. delete`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `commerceprice. privateoffers. get`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer) ( `roles/ commercepricemanagement.viewer` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `commerceprice. privateoffers. list`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer) ( `roles/ commercepricemanagement.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `commerceprice. privateoffers. publish`   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `commerceprice. privateoffers. sendEmail` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `commerceprice. privateoffers. update`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Commercepricemanagement Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor) ( `roles/ commercepricemanagement.editor` ) [Commerce Price Management Private Offers Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin) ( `roles/ commercepricemanagement.privateOffersAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
