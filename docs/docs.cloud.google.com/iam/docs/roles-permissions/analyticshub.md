---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/analyticshub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub
title: BigQuery sharing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery sharing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery sharing roles

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
<td>Analytics Hub Admin
<p>( <code>roles/ analyticshub.admin</code> )</p>
<p>Administer Data Exchanges and Listings</p></td>
<td><p><code>analyticshub. dataExchanges. create</code></p>
<p><code>analyticshub. dataExchanges. delete</code></p>
<p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub. dataExchanges. setIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. update</code></p>
<p><code>analyticshub. dataExchanges. viewSubscriptions</code></p>
<p><code>analyticshub.listings.create</code></p>
<p><code>analyticshub.listings.delete</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. listings. setIamPolicy</code></p>
<p><code>analyticshub.listings.update</code></p>
<p><code>analyticshub. listings. viewSubscriptions</code></p>
<p><code>analyticshub.queryTemplates.*</code></p>
<ul>
<li><code>analyticshub. queryTemplates. approve</code></li>
<li><code>analyticshub. queryTemplates. create</code></li>
<li><code>analyticshub. queryTemplates. delete</code></li>
<li><code>analyticshub. queryTemplates. get</code></li>
<li><code>analyticshub. queryTemplates. list</code></li>
<li><code>analyticshub. queryTemplates. update</code></li>
</ul>
<p><code>analyticshub.subscriptions.*</code></p>
<ul>
<li><code>analyticshub. subscriptions. create</code></li>
<li><code>analyticshub. subscriptions. delete</code></li>
<li><code>analyticshub.subscriptions.get</code></li>
<li><code>analyticshub. subscriptions. list</code></li>
<li><code>analyticshub. subscriptions. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Analytics Hub Editor
<p>( <code>roles/ analyticshub.editor</code> )</p>
<p>Editor role for Analytics Hub</p></td>
<td><p><code>analyticshub. dataExchanges. create</code></p>
<p><code>analyticshub. dataExchanges. delete</code></p>
<p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub. dataExchanges. update</code></p>
<p><code>analyticshub.listings.create</code></p>
<p><code>analyticshub.listings.delete</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub.listings.update</code></p>
<p><code>analyticshub.queryTemplates.*</code></p>
<ul>
<li><code>analyticshub. queryTemplates. approve</code></li>
<li><code>analyticshub. queryTemplates. create</code></li>
<li><code>analyticshub. queryTemplates. delete</code></li>
<li><code>analyticshub. queryTemplates. get</code></li>
<li><code>analyticshub. queryTemplates. list</code></li>
<li><code>analyticshub. queryTemplates. update</code></li>
</ul>
<p><code>analyticshub.subscriptions.*</code></p>
<ul>
<li><code>analyticshub. subscriptions. create</code></li>
<li><code>analyticshub. subscriptions. delete</code></li>
<li><code>analyticshub.subscriptions.get</code></li>
<li><code>analyticshub. subscriptions. list</code></li>
<li><code>analyticshub. subscriptions. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Analytics Hub Viewer
<p>( <code>roles/ analyticshub.viewer</code> )</p>
<p>Can browse Data Exchanges and Listings</p></td>
<td><p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. queryTemplates. get</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Analytics Hub Listing Admin
<p>( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p>Grants full control over the Listing, including updating, deleting and setting ACLs</p></td>
<td><p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub.listings.delete</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. listings. setIamPolicy</code></p>
<p><code>analyticshub.listings.update</code></p>
<p><code>analyticshub. listings. viewSubscriptions</code></p>
<p><code>analyticshub. queryTemplates. get</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Analytics Hub Publisher
<p>( <code>roles/ analyticshub.publisher</code> )</p>
<p>Can publish to Data Exchanges thus creating Listings</p></td>
<td><p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub.listings.create</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub.queryTemplates.*</code></p>
<ul>
<li><code>analyticshub. queryTemplates. approve</code></li>
<li><code>analyticshub. queryTemplates. create</code></li>
<li><code>analyticshub. queryTemplates. delete</code></li>
<li><code>analyticshub. queryTemplates. get</code></li>
<li><code>analyticshub. queryTemplates. list</code></li>
<li><code>analyticshub. queryTemplates. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Analytics Hub Subscriber
<p>( <code>roles/ analyticshub.subscriber</code> )</p>
<p>Can browse Data Exchanges and subscribe to Listings</p></td>
<td><p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub. dataExchanges. subscribe</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. listings. subscribe</code></p>
<p><code>analyticshub. queryTemplates. get</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Analytics Hub Subscription Owner
<p>( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p>Grants full control over the Subscription, including updating and deleting</p></td>
<td><p><code>analyticshub.dataExchanges.get</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub.listings.get</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. queryTemplates. get</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>analyticshub.subscriptions.*</code></p>
<ul>
<li><code>analyticshub. subscriptions. create</code></li>
<li><code>analyticshub. subscriptions. delete</code></li>
<li><code>analyticshub.subscriptions.get</code></li>
<li><code>analyticshub. subscriptions. list</code></li>
<li><code>analyticshub. subscriptions. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Analytics Hub Service Agent
<p>( <code>roles/ analyticshub.serviceAgent</code> )</p>
<p>Grants Analytics Hub Service Agent permissions required to manage resources in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>analyticshub. dataExchanges. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## BigQuery sharing permissions

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
<td><code>analyticshub. dataExchanges. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. dataExchanges. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub.dataExchanges.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. dataExchanges. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. dataExchanges. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.serviceAgent">Analytics Hub Service Agent</a> ( <code>roles/ analyticshub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>analyticshub. dataExchanges. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. dataExchanges. subscribe</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. dataExchanges. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. dataExchanges. viewSubscriptions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub.listings.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub.listings.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub.listings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. listings. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub.listings.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. listings. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. listings. subscribe</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub.listings.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. listings. viewSubscriptions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. queryTemplates. approve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. queryTemplates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. queryTemplates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. queryTemplates. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. queryTemplates. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. queryTemplates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. subscriptions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. subscriptions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub.subscriptions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>analyticshub. subscriptions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>analyticshub. subscriptions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p></td>
</tr>
</tbody>
</table>
