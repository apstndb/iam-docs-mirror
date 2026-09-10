---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement
title: Cloud Commerce Consumer Procurement roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Commerce Consumer Procurement. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Commerce Consumer Procurement roles

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
<td><h4 id="consumerprocurement.entitlementManager" class="role-title add-link" data-text="Consumer Procurement Entitlement Manager" tabindex="-1">Consumer Procurement Entitlement Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p>Allows managing entitlements and enabling, disabling, and inspecting service states for a consumer project.</p></td>
<td><p><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  grant</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  revoke</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  entitlements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  create</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.entitlementViewer" class="role-title add-link" data-text="Consumer Procurement Entitlement Viewer" tabindex="-1">Consumer Procurement Entitlement Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p>Allows inspecting entitlements and service states for a consumer project.</p></td>
<td><p><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  entitlements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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
<td><h4 id="consumerprocurement.eventsViewer" class="role-title add-link" data-text="Consumer Procurement Events Viewer" tabindex="-1">Consumer Procurement Events Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.eventsViewer</code> )</p>
<p>Allows viewing key events for an offer</p></td>
<td><p><code dir="ltr" translate="no">consumerprocurement.events.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.events.get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  events.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.licensePoolEditor" class="role-title add-link" data-text="Consumer Procurement License Pool Editor" tabindex="-1">Consumer Procurement License Pool Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.licensePoolEditor</code> )</p>
<p>Allows managing license pools and license assignments.</p></td>
<td><p><code dir="ltr" translate="no">consumerprocurement.  licensePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  assign</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  unassign</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.licensePoolViewer" class="role-title add-link" data-text="Consumer Procurement License Pool Viewer" tabindex="-1">Consumer Procurement License Pool Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.licensePoolViewer</code> )</p>
<p>Allows viewing license pools and license assignments.</p></td>
<td><p><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.orderAdmin" class="role-title add-link" data-text="Consumer Procurement Order Administrator" tabindex="-1">Consumer Procurement Order Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p>Allows managing purchases.</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  redeemPromotion</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  create</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.accounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  create</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  delete</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  grant</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  revoke</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.events.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.events.get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  events.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  licensePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  assign</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  unassign</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.orders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  cancel</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.orders.get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  modify</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  place</code></li>
</ul>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  distribute</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  get</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  retract</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.orderViewer" class="role-title add-link" data-text="Consumer Procurement Order Viewer" tabindex="-1">Consumer Procurement Order Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p>Allows inspecting purchases.</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  accounts.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.orders.get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.procurementAdmin" class="role-title add-link" data-text="Consumer Procurement Administrator" tabindex="-1">Consumer Procurement Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p>Allows managing purchases, consents at both billing account and project level.</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  redeemPromotion</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  create</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  create</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  delete</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  consents.  allowProjectGrant</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  consents.  grant</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  consents.  revoke</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.events.get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  events.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  create</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  assign</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  unassign</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  licensePools.  update</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  update</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  cancel</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.orders.get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  modify</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  orders.  place</code></li>
</ul>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  distribute</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  get</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  retract</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.procurementViewer" class="role-title add-link" data-text="Consumer Procurement Viewer" tabindex="-1">Consumer Procurement Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p>Allows inspecting purchases, consents and entitlements and service states for a consumer project.</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  accounts.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  entitlements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  get</code></li>
<li><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.orders.get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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

## Cloud Commerce Consumer Procurement permissions

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
<td><h4 id="consumerprocurement.accounts.create" class="permission-name add-link" data-text="consumerprocurement.accounts.create" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  accounts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.accounts.delete" class="permission-name add-link" data-text="consumerprocurement.accounts.delete" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  accounts.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.accounts.get" class="permission-name add-link" data-text="consumerprocurement.accounts.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  accounts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.accounts.list" class="permission-name add-link" data-text="consumerprocurement.accounts.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.consents.allowProjectGrant" class="permission-name add-link" data-text="consumerprocurement.consents.allowProjectGrant" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  consents.  allowProjectGrant</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.consents.check" class="permission-name add-link" data-text="consumerprocurement.consents.check" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  consents.  check</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.consents.grant" class="permission-name add-link" data-text="consumerprocurement.consents.grant" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  consents.  grant</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.consents.list" class="permission-name add-link" data-text="consumerprocurement.consents.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.consents.revoke" class="permission-name add-link" data-text="consumerprocurement.consents.revoke" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  consents.  revoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.entitlements.get" class="permission-name add-link" data-text="consumerprocurement.entitlements.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  entitlements.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.admin">Commerce Organization Governance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.viewer">Commerce Organization Governance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.user">Governed Marketplace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.entitlements.list" class="permission-name add-link" data-text="consumerprocurement.entitlements.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.admin">Commerce Organization Governance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.viewer">Commerce Organization Governance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.user">Governed Marketplace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  commerceorggovernance.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.events.get" class="permission-name add-link" data-text="consumerprocurement.events.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.events.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.eventsViewer">Consumer Procurement Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.events.list" class="permission-name add-link" data-text="consumerprocurement.events.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  events.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.eventsViewer">Consumer Procurement Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.freeTrials.create" class="permission-name add-link" data-text="consumerprocurement.freeTrials.create" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.freeTrials.get" class="permission-name add-link" data-text="consumerprocurement.freeTrials.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.freeTrials.list" class="permission-name add-link" data-text="consumerprocurement.freeTrials.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.licensePools.assign" class="permission-name add-link" data-text="consumerprocurement.licensePools.assign" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  licensePools.  assign</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolEditor">Consumer Procurement License Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.licensePools.enumerateLicensedUsers" class="permission-name add-link" data-text="consumerprocurement.licensePools.enumerateLicensedUsers" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  licensePools.  enumerateLicensedUsers</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolEditor">Consumer Procurement License Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolViewer">Consumer Procurement License Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.licensePools.get" class="permission-name add-link" data-text="consumerprocurement.licensePools.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  licensePools.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolEditor">Consumer Procurement License Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolViewer">Consumer Procurement License Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.licensePools.unassign" class="permission-name add-link" data-text="consumerprocurement.licensePools.unassign" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  licensePools.  unassign</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolEditor">Consumer Procurement License Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.licensePools.update" class="permission-name add-link" data-text="consumerprocurement.licensePools.update" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  licensePools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.licensePoolEditor">Consumer Procurement License Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.licensePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.orderAttributions.get" class="permission-name add-link" data-text="consumerprocurement.orderAttributions.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.orderAttributions.list" class="permission-name add-link" data-text="consumerprocurement.orderAttributions.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.orderAttributions.update" class="permission-name add-link" data-text="consumerprocurement.orderAttributions.update" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.orders.cancel" class="permission-name add-link" data-text="consumerprocurement.orders.cancel" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orders.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.orders.get" class="permission-name add-link" data-text="consumerprocurement.orders.get" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.orders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.orders.list" class="permission-name add-link" data-text="consumerprocurement.orders.list" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="consumerprocurement.orders.modify" class="permission-name add-link" data-text="consumerprocurement.orders.modify" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orders.  modify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="consumerprocurement.orders.place" class="permission-name add-link" data-text="consumerprocurement.orders.place" tabindex="-1"><code dir="ltr" translate="no">consumerprocurement.  orders.  place</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
</tbody>
</table>
