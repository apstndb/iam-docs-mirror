---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/billing
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/billing
title: Cloud Billing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Billing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Billing roles

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
<td><h4 id="billing.admin" class="role-title add-link" data-text="Billing Account Administrator" tabindex="-1">Billing Account Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p>Provides access to see and manage all aspects of billing accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">billing.accounts.close</code></p>
<p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getCarbonInformation</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getPaymentInfo</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getPricing</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformation</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getUsageExportSpec</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.accounts.move</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  redeemPromotion</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  removeFromOrganization</code></p>
<p><code dir="ltr" translate="no">billing.accounts.reopen</code></p>
<p><code dir="ltr" translate="no">billing.accounts.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.update</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  updatePaymentInfo</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  updateUsageExportSpec</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.anomalies.get</code></li>
<li><code dir="ltr" translate="no">billing.anomalies.list</code></li>
<li><code dir="ltr" translate="no">billing.  anomalies.  submitFeedback</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.anomaliesConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.anomaliesConfigs.get</code></li>
<li><code dir="ltr" translate="no">billing.  anomaliesConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountPrice.  get</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountServices.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountServices.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.billingAccountSkus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.billingAccountSkus.get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.budgets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.budgets.create</code></li>
<li><code dir="ltr" translate="no">billing.budgets.delete</code></li>
<li><code dir="ltr" translate="no">billing.budgets.get</code></li>
<li><code dir="ltr" translate="no">billing.budgets.list</code></li>
<li><code dir="ltr" translate="no">billing.budgets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  finOpsBenchmarkInformation.  get</code></p>
<p><code dir="ltr" translate="no">billing.  finOpsHealthInformation.  get</code></p>
<p><code dir="ltr" translate="no">billing.resourceAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  resourceAssociations.  create</code></li>
<li><code dir="ltr" translate="no">billing.  resourceAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">billing.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">billing.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">billing.subscriptions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">chroniclesm.contracts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chroniclesm.contracts.get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.contracts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsupport.techCases.create</code></li>
<li><code dir="ltr" translate="no">cloudsupport.  techCases.  escalate</code></li>
<li><code dir="ltr" translate="no">cloudsupport.techCases.get</code></li>
<li><code dir="ltr" translate="no">cloudsupport.techCases.list</code></li>
<li><code dir="ltr" translate="no">cloudsupport.techCases.update</code></li>
</ul>
<p><code dir="ltr" translate="no">commerceoffercatalog.*</code></p>
<ul>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  get</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></li>
<li><code dir="ltr" translate="no">commerceoffercatalog.  offers.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.commitments.create</code></p>
<p><code dir="ltr" translate="no">compute.commitments.get</code></p>
<p><code dir="ltr" translate="no">compute.commitments.list</code></p>
<p><code dir="ltr" translate="no">compute.commitments.update</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  updateReservations</code></p>
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
<p><code dir="ltr" translate="no">dataprocessing.datasources.get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  distribute</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  get</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></li>
<li><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  retract</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.privateLogEntries.list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMachineTypeRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.costInsights.get</code></li>
<li><code dir="ltr" translate="no">recommender.costInsights.list</code></li>
<li><code dir="ltr" translate="no">recommender.  costInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  costRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  costRecommendations.  listAll</code></li>
<li><code dir="ltr" translate="no">recommender.  costRecommendations.  summarizeAll</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommenderConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommenderConfig.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommenderConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  createBillingAssignment</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  deleteBillingAssignment</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="billing.projectManager" class="role-title add-link" data-text="Project Billing Manager" tabindex="-1">Project Billing Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.projectManager</code> )</p>
<p>When granted in conjunction with the Billing Account User role, provides access to assign a project's billing account or disable its billing.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  projects.  createBillingAssignment</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  deleteBillingAssignment</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.viewer" class="role-title add-link" data-text="Billing Account Viewer" tabindex="-1">Billing Account Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p>View billing account cost and pricing information, transactions, and billing and commitment recommendations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getCarbonInformation</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getPaymentInfo</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getPricing</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformation</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getUsageExportSpec</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.get</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.list</code></p>
<p><code dir="ltr" translate="no">billing.anomaliesConfigs.get</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrice.  get</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountServices.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountServices.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.billingAccountSkus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.billingAccountSkus.get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.budgets.get</code></p>
<p><code dir="ltr" translate="no">billing.budgets.list</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  finOpsBenchmarkInformation.  get</code></p>
<p><code dir="ltr" translate="no">billing.  finOpsHealthInformation.  get</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></p>
<p><code dir="ltr" translate="no">billing.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">billing.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.contracts.get</code></p>
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
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.orders.get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.datasources.get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.get</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.list</code></p>
<p><code dir="ltr" translate="no">recommender.  costRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  costRecommendations.  listAll</code></li>
<li><code dir="ltr" translate="no">recommender.  costRecommendations.  summarizeAll</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="billing.carbonViewer" class="role-title add-link" data-text="Carbon Footprint Viewer" tabindex="-1">Carbon Footprint Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.carbonViewer</code> )</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getCarbonInformation</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.costsManager" class="role-title add-link" data-text="Billing Account Costs Manager" tabindex="-1">Billing Account Costs Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p>Manage budgets for a billing account, and view, analyze, and export cost information of a billing account.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformation</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getUsageExportSpec</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  updateUsageExportSpec</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.get</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.list</code></p>
<p><code dir="ltr" translate="no">billing.anomaliesConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.anomaliesConfigs.get</code></li>
<li><code dir="ltr" translate="no">billing.  anomaliesConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.budgets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.budgets.create</code></li>
<li><code dir="ltr" translate="no">billing.budgets.delete</code></li>
<li><code dir="ltr" translate="no">billing.budgets.get</code></li>
<li><code dir="ltr" translate="no">billing.budgets.list</code></li>
<li><code dir="ltr" translate="no">billing.budgets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.costInsights.get</code></li>
<li><code dir="ltr" translate="no">recommender.costInsights.list</code></li>
<li><code dir="ltr" translate="no">recommender.  costInsights.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="billing.creator" class="role-title add-link" data-text="Billing Account Creator" tabindex="-1">Billing Account Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.creator</code> )</p>
<p>Provides access to create billing accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">billing.accounts.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.linkAdmin" class="role-title add-link" data-text="Account Hierarchy Manager" tabindex="-1">Account Hierarchy Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p>Authorized to manage billing account hierarchy</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.create</code></p>
<p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getCarbonInformation</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getPaymentInfo</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getPricing</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformation</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getUsageExportSpec</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.accounts.move</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  removeFromOrganization</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.get</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.list</code></p>
<p><code dir="ltr" translate="no">billing.anomaliesConfigs.get</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrice.  get</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountServices.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountServices.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.billingAccountSkus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">billing.billingAccountSkus.get</code></li>
<li><code dir="ltr" translate="no">billing.  billingAccountSkus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.budgets.get</code></p>
<p><code dir="ltr" translate="no">billing.budgets.list</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  finOpsBenchmarkInformation.  get</code></p>
<p><code dir="ltr" translate="no">billing.  finOpsHealthInformation.  get</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></p>
<p><code dir="ltr" translate="no">billing.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">billing.subscriptions.list</code></p>
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
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.orders.get</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.datasources.get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.get</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.list</code></p>
<p><code dir="ltr" translate="no">recommender.  costRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  costRecommendations.  listAll</code></li>
<li><code dir="ltr" translate="no">recommender.  costRecommendations.  summarizeAll</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="billing.projectCostsManager" class="role-title add-link" data-text="Project Billing Costs Manager" tabindex="-1">Project Billing Costs Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.projectCostsManager</code> )</p>
<p>When granted in conjunction with <a href="https://docs.cloud.google.com/billing/docs/how-to/custom-roles#cost_information">cost view permissions on projects</a> , provides access to billing information scoped to the projects to which the user has cost access.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformationScoped</code></p>
<p><code dir="ltr" translate="no">billing.  costRecommendations.  listScoped</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.user" class="role-title add-link" data-text="Billing Account User" tabindex="-1">Billing Account User</h4>
<p>( <code dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p>When granted in conjunction with the Project Owner role or Project Billing Manager role, provides access to associate projects with billing accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.  accounts.  redeemPromotion</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  create</code></p></td>
</tr>
</tbody>
</table>

## Cloud Billing permissions

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
<td><h4 id="billing.accounts.close" class="permission-name add-link" data-text="billing.accounts.close" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.close</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.create" class="permission-name add-link" data-text="billing.accounts.create" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.creator">Billing Account Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.creator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.get" class="permission-name add-link" data-text="billing.accounts.get" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.carbonViewer">Carbon Footprint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.carbonViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.projectCostsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountAdmin">BigQuery Recommender Billing Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsBillingAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountViewer">BigQuery Recommender Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsBillingAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudAdmin">Billing Account Usage Commitment Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.billingAccountCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudViewer">Billing Account Usage Commitment Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.billingAccountCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsAdmin">Spend Based Commitment Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.ucsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsViewer">Spend Based Commitment Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.ucsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.getCarbonInformation" class="permission-name add-link" data-text="billing.accounts.getCarbonInformation" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  getCarbonInformation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.carbonViewer">Carbon Footprint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.carbonViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.getIamPolicy" class="permission-name add-link" data-text="billing.accounts.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.projectCostsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.getPaymentInfo" class="permission-name add-link" data-text="billing.accounts.getPaymentInfo" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  getPaymentInfo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.getPricing" class="permission-name add-link" data-text="billing.accounts.getPricing" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.getPricing</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.getSpendingInformation" class="permission-name add-link" data-text="billing.accounts.getSpendingInformation" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.getSpendingInformationScoped" class="permission-name add-link" data-text="billing.accounts.getSpendingInformationScoped" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  getSpendingInformationScoped</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.projectCostsManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.getUsageExportSpec" class="permission-name add-link" data-text="billing.accounts.getUsageExportSpec" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  getUsageExportSpec</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.list" class="permission-name add-link" data-text="billing.accounts.list" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.carbonViewer">Carbon Footprint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.carbonViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountAdmin">BigQuery Recommender Billing Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsBillingAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountViewer">BigQuery Recommender Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.bigQueryCapacityCommitmentsBillingAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudAdmin">Billing Account Usage Commitment Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.billingAccountCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudViewer">Billing Account Usage Commitment Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.billingAccountCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsAdmin">Spend Based Commitment Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.ucsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsViewer">Spend Based Commitment Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.ucsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.move" class="permission-name add-link" data-text="billing.accounts.move" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.redeemPromotion" class="permission-name add-link" data-text="billing.accounts.redeemPromotion" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  redeemPromotion</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.removeFromOrganization" class="permission-name add-link" data-text="billing.accounts.removeFromOrganization" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  removeFromOrganization</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.reopen" class="permission-name add-link" data-text="billing.accounts.reopen" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.reopen</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.setIamPolicy" class="permission-name add-link" data-text="billing.accounts.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.update" class="permission-name add-link" data-text="billing.accounts.update" tabindex="-1"><code dir="ltr" translate="no">billing.accounts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.accounts.updatePaymentInfo" class="permission-name add-link" data-text="billing.accounts.updatePaymentInfo" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  updatePaymentInfo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.accounts.updateUsageExportSpec" class="permission-name add-link" data-text="billing.accounts.updateUsageExportSpec" tabindex="-1"><code dir="ltr" translate="no">billing.  accounts.  updateUsageExportSpec</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.anomalies.get" class="permission-name add-link" data-text="billing.anomalies.get" tabindex="-1"><code dir="ltr" translate="no">billing.anomalies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.anomalies.list" class="permission-name add-link" data-text="billing.anomalies.list" tabindex="-1"><code dir="ltr" translate="no">billing.anomalies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.anomalies.submitFeedback" class="permission-name add-link" data-text="billing.anomalies.submitFeedback" tabindex="-1"><code dir="ltr" translate="no">billing.  anomalies.  submitFeedback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.anomaliesConfigs.get" class="permission-name add-link" data-text="billing.anomaliesConfigs.get" tabindex="-1"><code dir="ltr" translate="no">billing.anomaliesConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.anomaliesConfigs.update" class="permission-name add-link" data-text="billing.anomaliesConfigs.update" tabindex="-1"><code dir="ltr" translate="no">billing.  anomaliesConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.billingAccountPrice.get" class="permission-name add-link" data-text="billing.billingAccountPrice.get" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountPrice.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.billingAccountPrices.list" class="permission-name add-link" data-text="billing.billingAccountPrices.list" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountPrices.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.billingAccountServices.get" class="permission-name add-link" data-text="billing.billingAccountServices.get" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountServices.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.billingAccountServices.list" class="permission-name add-link" data-text="billing.billingAccountServices.list" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountServices.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.billingAccountSkuGroupSkus.get" class="permission-name add-link" data-text="billing.billingAccountSkuGroupSkus.get" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.billingAccountSkuGroupSkus.list" class="permission-name add-link" data-text="billing.billingAccountSkuGroupSkus.list" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.billingAccountSkuGroups.get" class="permission-name add-link" data-text="billing.billingAccountSkuGroups.get" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.billingAccountSkuGroups.list" class="permission-name add-link" data-text="billing.billingAccountSkuGroups.list" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.billingAccountSkus.get" class="permission-name add-link" data-text="billing.billingAccountSkus.get" tabindex="-1"><code dir="ltr" translate="no">billing.billingAccountSkus.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.billingAccountSkus.list" class="permission-name add-link" data-text="billing.billingAccountSkus.list" tabindex="-1"><code dir="ltr" translate="no">billing.  billingAccountSkus.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.budgets.create" class="permission-name add-link" data-text="billing.budgets.create" tabindex="-1"><code dir="ltr" translate="no">billing.budgets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.budgets.delete" class="permission-name add-link" data-text="billing.budgets.delete" tabindex="-1"><code dir="ltr" translate="no">billing.budgets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.budgets.get" class="permission-name add-link" data-text="billing.budgets.get" tabindex="-1"><code dir="ltr" translate="no">billing.budgets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.budgets.list" class="permission-name add-link" data-text="billing.budgets.list" tabindex="-1"><code dir="ltr" translate="no">billing.budgets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.budgets.update" class="permission-name add-link" data-text="billing.budgets.update" tabindex="-1"><code dir="ltr" translate="no">billing.budgets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.costRecommendations.listScoped" class="permission-name add-link" data-text="billing.costRecommendations.listScoped" tabindex="-1"><code dir="ltr" translate="no">billing.  costRecommendations.  listScoped</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.projectCostsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.credits.list" class="permission-name add-link" data-text="billing.credits.list" tabindex="-1"><code dir="ltr" translate="no">billing.credits.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.finOpsBenchmarkInformation.get" class="permission-name add-link" data-text="billing.finOpsBenchmarkInformation.get" tabindex="-1"><code dir="ltr" translate="no">billing.  finOpsBenchmarkInformation.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.finOpsHealthInformation.get" class="permission-name add-link" data-text="billing.finOpsHealthInformation.get" tabindex="-1"><code dir="ltr" translate="no">billing.  finOpsHealthInformation.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.resourceAssociations.create" class="permission-name add-link" data-text="billing.resourceAssociations.create" tabindex="-1"><code dir="ltr" translate="no">billing.  resourceAssociations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  consumerprocurement.procurementAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="billing.resourceAssociations.delete" class="permission-name add-link" data-text="billing.resourceAssociations.delete" tabindex="-1"><code dir="ltr" translate="no">billing.  resourceAssociations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.resourceAssociations.list" class="permission-name add-link" data-text="billing.resourceAssociations.list" tabindex="-1"><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.resourceCosts.get" class="permission-name add-link" data-text="billing.resourceCosts.get" tabindex="-1"><code dir="ltr" translate="no">billing.resourceCosts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.resourcebudgets.read" class="permission-name add-link" data-text="billing.resourcebudgets.read" tabindex="-1"><code dir="ltr" translate="no">billing.resourcebudgets.read</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.resourcebudgets.write" class="permission-name add-link" data-text="billing.resourcebudgets.write" tabindex="-1"><code dir="ltr" translate="no">billing.resourcebudgets.write</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="billing.subscriptions.create" class="permission-name add-link" data-text="billing.subscriptions.create" tabindex="-1"><code dir="ltr" translate="no">billing.subscriptions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.subscriptions.get" class="permission-name add-link" data-text="billing.subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">billing.subscriptions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="billing.subscriptions.list" class="permission-name add-link" data-text="billing.subscriptions.list" tabindex="-1"><code dir="ltr" translate="no">billing.subscriptions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="billing.subscriptions.update" class="permission-name add-link" data-text="billing.subscriptions.update" tabindex="-1"><code dir="ltr" translate="no">billing.subscriptions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p></td>
</tr>
</tbody>
</table>
