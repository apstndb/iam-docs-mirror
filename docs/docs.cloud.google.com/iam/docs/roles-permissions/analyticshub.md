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
<td><h4 id="analyticshub.admin" class="role-title add-link" data-text="Analytics Hub Admin" tabindex="-1">Analytics Hub Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p>Administer Data Exchanges and Listings</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  create</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  delete</code></p>
<p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  update</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  viewSubscriptions</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.create</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.delete</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.update</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  viewSubscriptions</code></p>
<p><code dir="ltr" translate="no">analyticshub.subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  create</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">analyticshub.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  list</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.editor" class="role-title add-link" data-text="Analytics Hub Editor" tabindex="-1">Analytics Hub Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p>Editor role for Analytics Hub</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  create</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  delete</code></p>
<p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  update</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.create</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.delete</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.update</code></p>
<p><code dir="ltr" translate="no">analyticshub.subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  create</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">analyticshub.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  list</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.viewer" class="role-title add-link" data-text="Analytics Hub Viewer" tabindex="-1">Analytics Hub Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p>Can browse Data Exchanges and Listings</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.listingAdmin" class="role-title add-link" data-text="Analytics Hub Listing Admin" tabindex="-1">Analytics Hub Listing Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p>Grants full control over the Listing, including updating, deleting and setting ACLs</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.delete</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.update</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  viewSubscriptions</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.publisher" class="role-title add-link" data-text="Analytics Hub Publisher" tabindex="-1">Analytics Hub Publisher</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p>Can publish to Data Exchanges thus creating Listings</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.create</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.subscriber" class="role-title add-link" data-text="Analytics Hub Subscriber" tabindex="-1">Analytics Hub Subscriber</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p>Can browse Data Exchanges and subscribe to Listings</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  subscribe</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  subscribe</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.subscriptionOwner" class="role-title add-link" data-text="Analytics Hub Subscription Owner" tabindex="-1">Analytics Hub Subscription Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p>Grants full control over the Subscription, including updating and deleting</p></td>
<td><p><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.get</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  create</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">analyticshub.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  list</code></li>
<li><code dir="ltr" translate="no">analyticshub.  subscriptions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="analyticshub.dataExchanges.create" class="permission-name add-link" data-text="analyticshub.dataExchanges.create" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.dataExchanges.delete" class="permission-name add-link" data-text="analyticshub.dataExchanges.delete" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.dataExchanges.get" class="permission-name add-link" data-text="analyticshub.dataExchanges.get" tabindex="-1"><code dir="ltr" translate="no">analyticshub.dataExchanges.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.dataExchanges.getIamPolicy" class="permission-name add-link" data-text="analyticshub.dataExchanges.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.dataExchanges.list" class="permission-name add-link" data-text="analyticshub.dataExchanges.list" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.dataExchanges.setIamPolicy" class="permission-name add-link" data-text="analyticshub.dataExchanges.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.dataExchanges.subscribe" class="permission-name add-link" data-text="analyticshub.dataExchanges.subscribe" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  subscribe</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.dataExchanges.update" class="permission-name add-link" data-text="analyticshub.dataExchanges.update" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.dataExchanges.viewSubscriptions" class="permission-name add-link" data-text="analyticshub.dataExchanges.viewSubscriptions" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  dataExchanges.  viewSubscriptions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.listings.create" class="permission-name add-link" data-text="analyticshub.listings.create" tabindex="-1"><code dir="ltr" translate="no">analyticshub.listings.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.listings.delete" class="permission-name add-link" data-text="analyticshub.listings.delete" tabindex="-1"><code dir="ltr" translate="no">analyticshub.listings.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.listings.get" class="permission-name add-link" data-text="analyticshub.listings.get" tabindex="-1"><code dir="ltr" translate="no">analyticshub.listings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.listings.getIamPolicy" class="permission-name add-link" data-text="analyticshub.listings.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.listings.list" class="permission-name add-link" data-text="analyticshub.listings.list" tabindex="-1"><code dir="ltr" translate="no">analyticshub.listings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.listings.setIamPolicy" class="permission-name add-link" data-text="analyticshub.listings.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  listings.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.listings.subscribe" class="permission-name add-link" data-text="analyticshub.listings.subscribe" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  listings.  subscribe</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.listings.update" class="permission-name add-link" data-text="analyticshub.listings.update" tabindex="-1"><code dir="ltr" translate="no">analyticshub.listings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.listings.viewSubscriptions" class="permission-name add-link" data-text="analyticshub.listings.viewSubscriptions" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  listings.  viewSubscriptions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.listingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.subscriptions.create" class="permission-name add-link" data-text="analyticshub.subscriptions.create" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  subscriptions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.subscriptions.delete" class="permission-name add-link" data-text="analyticshub.subscriptions.delete" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  subscriptions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.subscriptions.get" class="permission-name add-link" data-text="analyticshub.subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">analyticshub.subscriptions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="analyticshub.subscriptions.list" class="permission-name add-link" data-text="analyticshub.subscriptions.list" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  subscriptions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="analyticshub.subscriptions.update" class="permission-name add-link" data-text="analyticshub.subscriptions.update" tabindex="-1"><code dir="ltr" translate="no">analyticshub.  subscriptions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  analyticshub.subscriptionOwner</code> )</p></td>
</tr>
</tbody>
</table>
