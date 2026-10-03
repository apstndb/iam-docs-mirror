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
<td>Billing Account Administrator
<p>( <code>roles/ billing.admin</code> )</p>
<p>Provides access to see and manage all aspects of billing accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code>billing.accounts.close</code></p>
<p><code>billing.accounts.get</code></p>
<p><code>billing. accounts. getCarbonInformation</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing. accounts. getPaymentInfo</code></p>
<p><code>billing.accounts.getPricing</code></p>
<p><code>billing. accounts. getSpendingInformation</code></p>
<p><code>billing. accounts. getUsageExportSpec</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing.accounts.move</code></p>
<p><code>billing. accounts. redeemPromotion</code></p>
<p><code>billing. accounts. removeFromOrganization</code></p>
<p><code>billing.accounts.reopen</code></p>
<p><code>billing.accounts.setIamPolicy</code></p>
<p><code>billing.accounts.update</code></p>
<p><code>billing. accounts. updatePaymentInfo</code></p>
<p><code>billing. accounts. updateUsageExportSpec</code></p>
<p><code>billing.anomalies.*</code></p>
<ul>
<li><code>billing.anomalies.get</code></li>
<li><code>billing.anomalies.list</code></li>
<li><code>billing. anomalies. submitFeedback</code></li>
</ul>
<p><code>billing.anomaliesConfigs.*</code></p>
<ul>
<li><code>billing.anomaliesConfigs.get</code></li>
<li><code>billing. anomaliesConfigs. update</code></li>
</ul>
<p><code>billing. billingAccountPrice. get</code></p>
<p><code>billing. billingAccountPrices. list</code></p>
<p><code>billing. billingAccountServices.*</code></p>
<ul>
<li><code>billing. billingAccountServices. get</code></li>
<li><code>billing. billingAccountServices. list</code></li>
</ul>
<p><code>billing. billingAccountSkuGroupSkus.*</code></p>
<ul>
<li><code>billing. billingAccountSkuGroupSkus. get</code></li>
<li><code>billing. billingAccountSkuGroupSkus. list</code></li>
</ul>
<p><code>billing. billingAccountSkuGroups.*</code></p>
<ul>
<li><code>billing. billingAccountSkuGroups. get</code></li>
<li><code>billing. billingAccountSkuGroups. list</code></li>
</ul>
<p><code>billing.billingAccountSkus.*</code></p>
<ul>
<li><code>billing.billingAccountSkus.get</code></li>
<li><code>billing. billingAccountSkus. list</code></li>
</ul>
<p><code>billing.budgets.*</code></p>
<ul>
<li><code>billing. budgets. configureSpendCap</code></li>
<li><code>billing.budgets.create</code></li>
<li><code>billing.budgets.delete</code></li>
<li><code>billing.budgets.get</code></li>
<li><code>billing.budgets.list</code></li>
<li><code>billing.budgets.update</code></li>
</ul>
<p><code>billing.credits.list</code></p>
<p><code>billing. finOpsBenchmarkInformation. get</code></p>
<p><code>billing. finOpsHealthInformation. get</code></p>
<p><code>billing.resourceAssociations.*</code></p>
<ul>
<li><code>billing. resourceAssociations. create</code></li>
<li><code>billing. resourceAssociations. delete</code></li>
<li><code>billing. resourceAssociations. list</code></li>
</ul>
<p><code>billing.subscriptions.*</code></p>
<ul>
<li><code>billing.subscriptions.create</code></li>
<li><code>billing.subscriptions.get</code></li>
<li><code>billing.subscriptions.list</code></li>
<li><code>billing.subscriptions.update</code></li>
</ul>
<p><code>chroniclesm.contracts.*</code></p>
<ul>
<li><code>chroniclesm.contracts.get</code></li>
<li><code>chroniclesm.contracts.update</code></li>
</ul>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudsupport.properties.get</code></p>
<p><code>cloudsupport.techCases.*</code></p>
<ul>
<li><code>cloudsupport.techCases.create</code></li>
<li><code>cloudsupport. techCases. escalate</code></li>
<li><code>cloudsupport.techCases.get</code></li>
<li><code>cloudsupport.techCases.list</code></li>
<li><code>cloudsupport.techCases.update</code></li>
</ul>
<p><code>commerceoffercatalog.*</code></p>
<ul>
<li><code>commerceoffercatalog. agreements. get</code></li>
<li><code>commerceoffercatalog. agreements. list</code></li>
<li><code>commerceoffercatalog. documents. get</code></li>
<li><code>commerceoffercatalog. documents. list</code></li>
<li><code>commerceoffercatalog. offers. get</code></li>
</ul>
<p><code>compute.commitments.create</code></p>
<p><code>compute.commitments.get</code></p>
<p><code>compute.commitments.list</code></p>
<p><code>compute.commitments.update</code></p>
<p><code>compute. commitments. updateReservations</code></p>
<p><code>consumerprocurement.accounts.*</code></p>
<ul>
<li><code>consumerprocurement. accounts. create</code></li>
<li><code>consumerprocurement. accounts. delete</code></li>
<li><code>consumerprocurement. accounts. get</code></li>
<li><code>consumerprocurement. accounts. list</code></li>
</ul>
<p><code>consumerprocurement. consents. check</code></p>
<p><code>consumerprocurement. consents. grant</code></p>
<p><code>consumerprocurement. consents. list</code></p>
<p><code>consumerprocurement. consents. revoke</code></p>
<p><code>consumerprocurement.events.*</code></p>
<ul>
<li><code>consumerprocurement.events.get</code></li>
<li><code>consumerprocurement. events. list</code></li>
</ul>
<p><code>consumerprocurement. licensePools.*</code></p>
<ul>
<li><code>consumerprocurement. licensePools. assign</code></li>
<li><code>consumerprocurement. licensePools. enumerateLicensedUsers</code></li>
<li><code>consumerprocurement. licensePools. get</code></li>
<li><code>consumerprocurement. licensePools. unassign</code></li>
<li><code>consumerprocurement. licensePools. update</code></li>
</ul>
<p><code>consumerprocurement. orderAttributions.*</code></p>
<ul>
<li><code>consumerprocurement. orderAttributions. get</code></li>
<li><code>consumerprocurement. orderAttributions. list</code></li>
<li><code>consumerprocurement. orderAttributions. update</code></li>
</ul>
<p><code>consumerprocurement.orders.*</code></p>
<ul>
<li><code>consumerprocurement. orders. cancel</code></li>
<li><code>consumerprocurement.orders.get</code></li>
<li><code>consumerprocurement. orders. list</code></li>
<li><code>consumerprocurement. orders. modify</code></li>
<li><code>consumerprocurement. orders. place</code></li>
</ul>
<p><code>dataprocessing.datasources.get</code></p>
<p><code>dataprocessing. datasources. list</code></p>
<p><code>dataprocessing. groupcontrols. get</code></p>
<p><code>dataprocessing. groupcontrols. list</code></p>
<p><code>discoveryengine. billingAccountLicenseConfigs.*</code></p>
<ul>
<li><code>discoveryengine. billingAccountLicenseConfigs. distribute</code></li>
<li><code>discoveryengine. billingAccountLicenseConfigs. get</code></li>
<li><code>discoveryengine. billingAccountLicenseConfigs. list</code></li>
<li><code>discoveryengine. billingAccountLicenseConfigs. retract</code></li>
</ul>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.privateLogEntries.list</code></p>
<p><code>recommender. cloudsqlIdleInstanceRecommendations. get</code></p>
<p><code>recommender. cloudsqlIdleInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. get</code></p>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. list</code></p>
<p><code>recommender. commitmentUtilizationInsights.*</code></p>
<ul>
<li><code>recommender. commitmentUtilizationInsights. get</code></li>
<li><code>recommender. commitmentUtilizationInsights. list</code></li>
<li><code>recommender. commitmentUtilizationInsights. update</code></li>
</ul>
<p><code>recommender. computeAddressIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeAddressIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeDiskIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeDiskIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeImageIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeImageIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMachineTypeRecommendations. get</code></p>
<p><code>recommender. computeInstanceGroupManagerMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommendations. get</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommendations. list</code></p>
<p><code>recommender.costInsights.*</code></p>
<ul>
<li><code>recommender.costInsights.get</code></li>
<li><code>recommender.costInsights.list</code></li>
<li><code>recommender. costInsights. update</code></li>
</ul>
<p><code>recommender. costRecommendations.*</code></p>
<ul>
<li><code>recommender. costRecommendations. listAll</code></li>
<li><code>recommender. costRecommendations. summarizeAll</code></li>
</ul>
<p><code>recommender. resourcemanagerProjectUtilizationRecommendations. get</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentInsights.*</code></p>
<ul>
<li><code>recommender. spendBasedCommitmentInsights. get</code></li>
<li><code>recommender. spendBasedCommitmentInsights. list</code></li>
<li><code>recommender. spendBasedCommitmentInsights. update</code></li>
</ul>
<p><code>recommender. spendBasedCommitmentRecommendations.*</code></p>
<ul>
<li><code>recommender. spendBasedCommitmentRecommendations. get</code></li>
<li><code>recommender. spendBasedCommitmentRecommendations. list</code></li>
<li><code>recommender. spendBasedCommitmentRecommendations. update</code></li>
</ul>
<p><code>recommender. spendBasedCommitmentRecommenderConfig.*</code></p>
<ul>
<li><code>recommender. spendBasedCommitmentRecommenderConfig. get</code></li>
<li><code>recommender. spendBasedCommitmentRecommenderConfig. update</code></li>
</ul>
<p><code>recommender. usageCommitmentRecommendations.*</code></p>
<ul>
<li><code>recommender. usageCommitmentRecommendations. get</code></li>
<li><code>recommender. usageCommitmentRecommendations. list</code></li>
<li><code>recommender. usageCommitmentRecommendations. update</code></li>
</ul>
<p><code>resourcemanager. projects. createBillingAssignment</code></p>
<p><code>resourcemanager. projects. deleteBillingAssignment</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Project Billing Manager
<p>( <code>roles/ billing.projectManager</code> )</p>
<p>When granted in conjunction with the Billing Account User role, provides access to assign a project's billing account or disable its billing.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>resourcemanager. projects. createBillingAssignment</code></p>
<p><code>resourcemanager. projects. deleteBillingAssignment</code></p></td>
</tr>
<tr class="odd">
<td>Billing Account Viewer
<p>( <code>roles/ billing.viewer</code> )</p>
<p>View billing account cost and pricing information, transactions, and billing and commitment recommendations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code>billing.accounts.get</code></p>
<p><code>billing. accounts. getCarbonInformation</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing. accounts. getPaymentInfo</code></p>
<p><code>billing.accounts.getPricing</code></p>
<p><code>billing. accounts. getSpendingInformation</code></p>
<p><code>billing. accounts. getUsageExportSpec</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing.anomalies.get</code></p>
<p><code>billing.anomalies.list</code></p>
<p><code>billing.anomaliesConfigs.get</code></p>
<p><code>billing. billingAccountPrice. get</code></p>
<p><code>billing. billingAccountPrices. list</code></p>
<p><code>billing. billingAccountServices.*</code></p>
<ul>
<li><code>billing. billingAccountServices. get</code></li>
<li><code>billing. billingAccountServices. list</code></li>
</ul>
<p><code>billing. billingAccountSkuGroupSkus.*</code></p>
<ul>
<li><code>billing. billingAccountSkuGroupSkus. get</code></li>
<li><code>billing. billingAccountSkuGroupSkus. list</code></li>
</ul>
<p><code>billing. billingAccountSkuGroups.*</code></p>
<ul>
<li><code>billing. billingAccountSkuGroups. get</code></li>
<li><code>billing. billingAccountSkuGroups. list</code></li>
</ul>
<p><code>billing.billingAccountSkus.*</code></p>
<ul>
<li><code>billing.billingAccountSkus.get</code></li>
<li><code>billing. billingAccountSkus. list</code></li>
</ul>
<p><code>billing.budgets.get</code></p>
<p><code>billing.budgets.list</code></p>
<p><code>billing.credits.list</code></p>
<p><code>billing. finOpsBenchmarkInformation. get</code></p>
<p><code>billing. finOpsHealthInformation. get</code></p>
<p><code>billing. resourceAssociations. list</code></p>
<p><code>billing.subscriptions.get</code></p>
<p><code>billing.subscriptions.list</code></p>
<p><code>chroniclesm.contracts.get</code></p>
<p><code>commerceoffercatalog.*</code></p>
<ul>
<li><code>commerceoffercatalog. agreements. get</code></li>
<li><code>commerceoffercatalog. agreements. list</code></li>
<li><code>commerceoffercatalog. documents. get</code></li>
<li><code>commerceoffercatalog. documents. list</code></li>
<li><code>commerceoffercatalog. offers. get</code></li>
</ul>
<p><code>consumerprocurement. accounts. get</code></p>
<p><code>consumerprocurement. accounts. list</code></p>
<p><code>consumerprocurement. consents. check</code></p>
<p><code>consumerprocurement. consents. list</code></p>
<p><code>consumerprocurement. orderAttributions. get</code></p>
<p><code>consumerprocurement. orderAttributions. list</code></p>
<p><code>consumerprocurement.orders.get</code></p>
<p><code>consumerprocurement. orders. list</code></p>
<p><code>dataprocessing.datasources.get</code></p>
<p><code>dataprocessing. datasources. list</code></p>
<p><code>dataprocessing. groupcontrols. get</code></p>
<p><code>dataprocessing. groupcontrols. list</code></p>
<p><code>discoveryengine. billingAccountLicenseConfigs. get</code></p>
<p><code>discoveryengine. billingAccountLicenseConfigs. list</code></p>
<p><code>recommender. commitmentUtilizationInsights. get</code></p>
<p><code>recommender. commitmentUtilizationInsights. list</code></p>
<p><code>recommender.costInsights.get</code></p>
<p><code>recommender.costInsights.list</code></p>
<p><code>recommender. costRecommendations.*</code></p>
<ul>
<li><code>recommender. costRecommendations. listAll</code></li>
<li><code>recommender. costRecommendations. summarizeAll</code></li>
</ul>
<p><code>recommender. spendBasedCommitmentInsights. get</code></p>
<p><code>recommender. spendBasedCommitmentInsights. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. get</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommenderConfig. get</code></p>
<p><code>recommender. usageCommitmentRecommendations. get</code></p>
<p><code>recommender. usageCommitmentRecommendations. list</code></p></td>
</tr>
<tr class="even">
<td>Carbon Footprint Viewer
<p>( <code>roles/ billing.carbonViewer</code> )</p></td>
<td><p><code>billing.accounts.get</code></p>
<p><code>billing. accounts. getCarbonInformation</code></p>
<p><code>billing.accounts.list</code></p></td>
</tr>
<tr class="odd">
<td>Billing Account Costs Manager
<p>( <code>roles/ billing.costsManager</code> )</p>
<p>Manage budgets for a billing account, and view, analyze, and export cost information of a billing account.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code>billing.accounts.get</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing. accounts. getSpendingInformation</code></p>
<p><code>billing. accounts. getUsageExportSpec</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing. accounts. updateUsageExportSpec</code></p>
<p><code>billing.anomalies.get</code></p>
<p><code>billing.anomalies.list</code></p>
<p><code>billing.anomaliesConfigs.*</code></p>
<ul>
<li><code>billing.anomaliesConfigs.get</code></li>
<li><code>billing. anomaliesConfigs. update</code></li>
</ul>
<p><code>billing.budgets.create</code></p>
<p><code>billing.budgets.delete</code></p>
<p><code>billing.budgets.get</code></p>
<p><code>billing.budgets.list</code></p>
<p><code>billing.budgets.update</code></p>
<p><code>billing. resourceAssociations. list</code></p>
<p><code>recommender.costInsights.*</code></p>
<ul>
<li><code>recommender.costInsights.get</code></li>
<li><code>recommender.costInsights.list</code></li>
<li><code>recommender. costInsights. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Billing Account Creator
<p>( <code>roles/ billing.creator</code> )</p>
<p>Provides access to create billing accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>billing.accounts.create</code></p>
<p><code>resourcemanager. organizations. get</code></p></td>
</tr>
<tr class="odd">
<td>Account Hierarchy Manager
<p>( <code>roles/ billing.linkAdmin</code> )</p>
<p>Authorized to manage billing account hierarchy</p></td>
<td><p><code>billing.accounts.create</code></p>
<p><code>billing.accounts.get</code></p>
<p><code>billing. accounts. getCarbonInformation</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing. accounts. getPaymentInfo</code></p>
<p><code>billing.accounts.getPricing</code></p>
<p><code>billing. accounts. getSpendingInformation</code></p>
<p><code>billing. accounts. getUsageExportSpec</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing.accounts.move</code></p>
<p><code>billing. accounts. removeFromOrganization</code></p>
<p><code>billing.anomalies.get</code></p>
<p><code>billing.anomalies.list</code></p>
<p><code>billing.anomaliesConfigs.get</code></p>
<p><code>billing. billingAccountPrice. get</code></p>
<p><code>billing. billingAccountPrices. list</code></p>
<p><code>billing. billingAccountServices.*</code></p>
<ul>
<li><code>billing. billingAccountServices. get</code></li>
<li><code>billing. billingAccountServices. list</code></li>
</ul>
<p><code>billing. billingAccountSkuGroupSkus.*</code></p>
<ul>
<li><code>billing. billingAccountSkuGroupSkus. get</code></li>
<li><code>billing. billingAccountSkuGroupSkus. list</code></li>
</ul>
<p><code>billing. billingAccountSkuGroups.*</code></p>
<ul>
<li><code>billing. billingAccountSkuGroups. get</code></li>
<li><code>billing. billingAccountSkuGroups. list</code></li>
</ul>
<p><code>billing.billingAccountSkus.*</code></p>
<ul>
<li><code>billing.billingAccountSkus.get</code></li>
<li><code>billing. billingAccountSkus. list</code></li>
</ul>
<p><code>billing.budgets.get</code></p>
<p><code>billing.budgets.list</code></p>
<p><code>billing.credits.list</code></p>
<p><code>billing. finOpsBenchmarkInformation. get</code></p>
<p><code>billing. finOpsHealthInformation. get</code></p>
<p><code>billing. resourceAssociations. list</code></p>
<p><code>billing.subscriptions.get</code></p>
<p><code>billing.subscriptions.list</code></p>
<p><code>commerceoffercatalog.*</code></p>
<ul>
<li><code>commerceoffercatalog. agreements. get</code></li>
<li><code>commerceoffercatalog. agreements. list</code></li>
<li><code>commerceoffercatalog. documents. get</code></li>
<li><code>commerceoffercatalog. documents. list</code></li>
<li><code>commerceoffercatalog. offers. get</code></li>
</ul>
<p><code>consumerprocurement. accounts. get</code></p>
<p><code>consumerprocurement. accounts. list</code></p>
<p><code>consumerprocurement. consents. check</code></p>
<p><code>consumerprocurement. consents. list</code></p>
<p><code>consumerprocurement. orderAttributions. get</code></p>
<p><code>consumerprocurement. orderAttributions. list</code></p>
<p><code>consumerprocurement.orders.get</code></p>
<p><code>consumerprocurement. orders. list</code></p>
<p><code>dataprocessing.datasources.get</code></p>
<p><code>dataprocessing. datasources. list</code></p>
<p><code>dataprocessing. groupcontrols. get</code></p>
<p><code>dataprocessing. groupcontrols. list</code></p>
<p><code>recommender. commitmentUtilizationInsights. get</code></p>
<p><code>recommender. commitmentUtilizationInsights. list</code></p>
<p><code>recommender.costInsights.get</code></p>
<p><code>recommender.costInsights.list</code></p>
<p><code>recommender. costRecommendations.*</code></p>
<ul>
<li><code>recommender. costRecommendations. listAll</code></li>
<li><code>recommender. costRecommendations. summarizeAll</code></li>
</ul>
<p><code>recommender. spendBasedCommitmentInsights. get</code></p>
<p><code>recommender. spendBasedCommitmentInsights. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. get</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommenderConfig. get</code></p>
<p><code>recommender. usageCommitmentRecommendations. get</code></p>
<p><code>recommender. usageCommitmentRecommendations. list</code></p></td>
</tr>
<tr class="even">
<td>Project Billing Costs Manager
<p>( <code>roles/ billing.projectCostsManager</code> )</p>
<p>When granted in conjunction with <a href="https://docs.cloud.google.com/billing/docs/how-to/custom-roles#cost_information">cost view permissions on projects</a> , provides access to billing information scoped to the projects to which the user has cost access.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code>billing.accounts.get</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing. accounts. getSpendingInformationScoped</code></p>
<p><code>billing. costRecommendations. listScoped</code></p></td>
</tr>
<tr class="odd">
<td>Billing Account User
<p>( <code>roles/ billing.user</code> )</p>
<p>When granted in conjunction with the Project Owner role or Project Billing Manager role, provides access to associate projects with billing accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Billing Account</li>
</ul></td>
<td><p><code>billing.accounts.get</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing. accounts. redeemPromotion</code></p>
<p><code>billing.credits.list</code></p>
<p><code>billing. resourceAssociations. create</code></p></td>
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
<td><code>billing.accounts.close</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.accounts.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.creator">Billing Account Creator</a> ( <code>roles/ billing.creator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.accounts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code>roles/ dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.carbonViewer">Carbon Footprint Viewer</a> ( <code>roles/ billing.carbonViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code>roles/ billing.projectCostsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code>roles/ billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code>roles/ consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code>roles/ consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountAdmin">BigQuery Recommender Billing Account Admin</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsBillingAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountViewer">BigQuery Recommender Billing Account Viewer</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsBillingAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudAdmin">Billing Account Usage Commitment Recommender Admin</a> ( <code>roles/ recommender.billingAccountCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudViewer">Billing Account Usage Commitment Recommender Viewer</a> ( <code>roles/ recommender.billingAccountCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsAdmin">Spend Based Commitment Recommender Admin</a> ( <code>roles/ recommender.ucsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsViewer">Spend Based Commitment Recommender Viewer</a> ( <code>roles/ recommender.ucsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>billing. accounts. getCarbonInformation</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.carbonViewer">Carbon Footprint Viewer</a> ( <code>roles/ billing.carbonViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.accounts.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code>roles/ billing.projectCostsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code>roles/ billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code>roles/ consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code>roles/ consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. accounts. getPaymentInfo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.accounts.getPricing</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. accounts. getSpendingInformation</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. accounts. getSpendingInformationScoped</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code>roles/ billing.projectCostsManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. accounts. getUsageExportSpec</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.accounts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code>roles/ dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.carbonViewer">Carbon Footprint Viewer</a> ( <code>roles/ billing.carbonViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code>roles/ billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code>roles/ consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code>roles/ consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountAdmin">BigQuery Recommender Billing Account Admin</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsBillingAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsBillingAccountViewer">BigQuery Recommender Billing Account Viewer</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsBillingAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudAdmin">Billing Account Usage Commitment Recommender Admin</a> ( <code>roles/ recommender.billingAccountCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.billingAccountCudViewer">Billing Account Usage Commitment Recommender Viewer</a> ( <code>roles/ recommender.billingAccountCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsAdmin">Spend Based Commitment Recommender Admin</a> ( <code>roles/ recommender.ucsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.ucsViewer">Spend Based Commitment Recommender Viewer</a> ( <code>roles/ recommender.ucsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.accounts.move</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. accounts. redeemPromotion</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code>roles/ billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code>roles/ consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. accounts. removeFromOrganization</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.accounts.reopen</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.accounts.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.accounts.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. accounts. updatePaymentInfo</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. accounts. updateUsageExportSpec</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.anomalies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.anomalies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. anomalies. submitFeedback</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.anomaliesConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. anomaliesConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. billingAccountPrice. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. billingAccountPrices. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. billingAccountServices. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. billingAccountServices. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. billingAccountSkuGroupSkus. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. billingAccountSkuGroupSkus. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. billingAccountSkuGroups. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. billingAccountSkuGroups. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.billingAccountSkus.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. billingAccountSkus. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. budgets. configureSpendCap</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.budgets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.budgets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.budgets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.budgets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.budgets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. costRecommendations. listScoped</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectCostsManager">Project Billing Costs Manager</a> ( <code>roles/ billing.projectCostsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.credits.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code>roles/ billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code>roles/ consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderViewer">Consumer Procurement Order Viewer</a> ( <code>roles/ consumerprocurement.orderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. finOpsBenchmarkInformation. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing. finOpsHealthInformation. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. resourceAssociations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.user">Billing Account User</a> ( <code>roles/ billing.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.orderAdmin">Consumer Procurement Order Administrator</a> ( <code>roles/ consumerprocurement.orderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>billing. resourceAssociations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. resourceAssociations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.costsManager">Billing Account Costs Manager</a> ( <code>roles/ billing.costsManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code>roles/ cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.resourceCosts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing. resourcebudgets. configureSpendCap</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.resourcebudgets.read</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.resourcebudgets.write</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>billing.subscriptions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.subscriptions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>billing.subscriptions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code>roles/ billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code>roles/ billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>billing.subscriptions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p></td>
</tr>
</tbody>
</table>
