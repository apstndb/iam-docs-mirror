---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription
title: Payments Reseller Subscription roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Payments Reseller Subscription. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Payments Reseller Subscription roles

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
<td><h4 id="paymentsresellersubscription.admin" class="role-title add-link" data-text="Paymentsresellersubscription Admin Beta" tabindex="-1">Paymentsresellersubscription Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p>Admin role for paymentsresellersubscription</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.*</code></p>
<ul>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptionLineItems.  update</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  cancel</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  extend</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  provision</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  resume</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  suspend</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  undoCancel</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  userSessions.  generate</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.viewer" class="role-title add-link" data-text="Paymentsresellersubscription Viewer Beta" tabindex="-1">Paymentsresellersubscription Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.viewer</code> )</p>
<p>Viewer role for paymentsresellersubscription</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.partnerAdmin" class="role-title add-link" data-text="Payments Reseller Admin Beta" tabindex="-1">Payments Reseller Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p>Full access to all Payments Reseller resources, including subscriptions, products and promotions</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.*</code></p>
<ul>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptionLineItems.  update</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  cancel</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  extend</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  provision</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  resume</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  suspend</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  undoCancel</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  userSessions.  generate</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.partnerViewer" class="role-title add-link" data-text="Payments Reseller Viewer Beta" tabindex="-1">Payments Reseller Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerViewer</code> )</p>
<p>Read access to all Payments Reseller resources, including subscriptions, products and promotions</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.productViewer" class="role-title add-link" data-text="Payments Reseller Products Viewer Beta" tabindex="-1">Payments Reseller Products Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.productViewer</code> )</p>
<p>Read access to Payments Reseller Product resource</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.promotionViewer" class="role-title add-link" data-text="Payments Reseller Promotions Viewer Beta" tabindex="-1">Payments Reseller Promotions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.promotionViewer</code> )</p>
<p>Read access to Payments Reseller Promotion resource</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.subscriptionEditor" class="role-title add-link" data-text="Payments Reseller Subscriptions Editor Beta" tabindex="-1">Payments Reseller Subscriptions Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p>
<p>Write access to Payments Reseller Subscription resource</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptionLineItems.  update</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  cancel</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  extend</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  provision</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  resume</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  suspend</code></li>
<li><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  undoCancel</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.subscriptionViewer" class="role-title add-link" data-text="Payments Reseller Subscriptions Viewer Beta" tabindex="-1">Payments Reseller Subscriptions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionViewer</code> )</p>
<p>Read access to Payments Reseller Subscription resource</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.userSessionEditor" class="role-title add-link" data-text="Payments Partner UserSessions Editor Beta" tabindex="-1">Payments Partner UserSessions Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  paymentsresellersubscription.userSessionEditor</code> )</p>
<p>Editor of UserSessions for a Payments Partner</p></td>
<td><p><code dir="ltr" translate="no">paymentsresellersubscription.  userSessions.  generate</code></p></td>
</tr>
</tbody>
</table>

## Payments Reseller Subscription permissions

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
<td><h4 id="paymentsresellersubscription.products.list" class="permission-name add-link" data-text="paymentsresellersubscription.products.list" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.productViewer">Payments Reseller Products Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.productViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.promotions.list" class="permission-name add-link" data-text="paymentsresellersubscription.promotions.list" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.promotionViewer">Payments Reseller Promotions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.promotionViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.subscriptionLineItems.update" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptionLineItems.update" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptionLineItems.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.subscriptions.cancel" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.cancel" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.subscriptions.extend" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.extend" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  extend</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.subscriptions.get" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionViewer">Payments Reseller Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.subscriptions.provision" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.provision" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  provision</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.subscriptions.resume" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.resume" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.subscriptions.suspend" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.suspend" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  suspend</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="paymentsresellersubscription.subscriptions.undoCancel" class="permission-name add-link" data-text="paymentsresellersubscription.subscriptions.undoCancel" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  subscriptions.  undoCancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.subscriptionEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="paymentsresellersubscription.userSessions.generate" class="permission-name add-link" data-text="paymentsresellersubscription.userSessions.generate" tabindex="-1"><code dir="ltr" translate="no">paymentsresellersubscription.  userSessions.  generate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.userSessionEditor">Payments Partner UserSessions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  paymentsresellersubscription.userSessionEditor</code> )</p></td>
</tr>
</tbody>
</table>
