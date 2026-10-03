---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/serviceusage
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage
title: Service Usage roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Usage. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Usage roles

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
<td>API Keys Admin
<p>( <code>roles/ serviceusage.apiKeysAdmin</code> )</p>
<p>Ability to create, delete, update, get and list API keys for a project.</p></td>
<td><p><code>apikeys.*</code></p>
<ul>
<li><code>apikeys.keys.create</code></li>
<li><code>apikeys.keys.delete</code></li>
<li><code>apikeys.keys.get</code></li>
<li><code>apikeys.keys.getKeyString</code></li>
<li><code>apikeys.keys.list</code></li>
<li><code>apikeys.keys.lookup</code></li>
<li><code>apikeys.keys.undelete</code></li>
<li><code>apikeys.keys.update</code></li>
</ul>
<p><code>orgpolicy.policy.get</code></p>
<p><code>serviceusage.apiKeys.*</code></p>
<ul>
<li><code>serviceusage. apiKeys. regenerate</code></li>
<li><code>serviceusage.apiKeys.revert</code></li>
</ul>
<p><code>serviceusage.operations.get</code></p></td>
</tr>
<tr class="even">
<td>Service Usage Admin
<p>( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p>Ability to enable, disable, and inspect service states, inspect operations, and consume quota and billing for a consumer project.</p></td>
<td><p><code>cloudquotas.*</code></p>
<ul>
<li><code>cloudquotas.quotas.get</code></li>
<li><code>cloudquotas.quotas.update</code></li>
</ul>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. contentsecuritypolicy.*</code></p>
<ul>
<li><code>serviceusage. contentsecuritypolicy. get</code></li>
<li><code>serviceusage. contentsecuritypolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.*</code></p>
<ul>
<li><code>serviceusage.mcppolicy.get</code></li>
<li><code>serviceusage.mcppolicy.update</code></li>
</ul>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.*</code></p>
<ul>
<li><code>serviceusage.quotas.get</code></li>
<li><code>serviceusage.quotas.update</code></li>
</ul>
<p><code>serviceusage.services.*</code></p>
<ul>
<li><code>serviceusage.services.disable</code></li>
<li><code>serviceusage.services.enable</code></li>
<li><code>serviceusage.services.get</code></li>
<li><code>serviceusage.services.list</code></li>
<li><code>serviceusage.services.use</code></li>
</ul>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Service Usage Consumer
<p>( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p>Ability to inspect service states and operations, and consume quota and billing for a consumer project.</p></td>
<td><p><code>monitoring.timeSeries.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Service Usage Viewer
<p>( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p>Ability to inspect service states and operations for a consumer project.</p></td>
<td><p><code>monitoring.timeSeries.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. contentsecuritypolicy. get</code></p>
<p><code>serviceusage. effectivemcppolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.mcppolicy.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>API Keys Viewer
<p>( <code>roles/ serviceusage.apiKeysViewer</code> )</p>
<p>Ability to get and list API keys for a project.</p></td>
<td><p><code>apikeys.keys.get</code></p>
<p><code>apikeys.keys.getKeyString</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>apikeys.keys.lookup</code></p></td>
</tr>
</tbody>
</table>

## Service Usage permissions

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
<td><code>serviceusage. apiKeys. regenerate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.apiKeysAdmin">API Keys Admin</a> ( <code>roles/ serviceusage.apiKeysAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>serviceusage.apiKeys.revert</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.apiKeysAdmin">API Keys Admin</a> ( <code>roles/ serviceusage.apiKeysAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>serviceusage. consumerpolicy. analyze</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage. consumerpolicy. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage. consumerpolicy. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage. contentsecuritypolicy. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage. contentsecuritypolicy. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>serviceusage. effectivemcppolicy. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.admin">Cloud API Registry Admin</a> ( <code>roles/ cloudapiregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudapiregistry#cloudapiregistry.viewer">Cloud API Registry Viewer</a> ( <code>roles/ cloudapiregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage. effectivepolicy. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage.groups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage. groups. listExpandedMembers</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage. groups. listMembers</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage.mcppolicy.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage.mcppolicy.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>serviceusage.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code>roles/ commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.apiKeysAdmin">API Keys Admin</a> ( <code>roles/ serviceusage.apiKeysAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage.quotas.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code>roles/ looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code>roles/ migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code>roles/ migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code>roles/ networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code>roles/ networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a> ( <code>roles/ spectrumsas.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage.quotas.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>serviceusage.services.disable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage.services.enable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code>roles/ commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage.services.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code>roles/ commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code>roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code>roles/ cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code>roles/ networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code>roles/ networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a> ( <code>roles/ aiplatform.onlinePredictionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code>roles/ edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a> ( <code>roles/ spectrumsas.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage.services.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code>roles/ retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code>roles/ retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code>roles/ retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code>roles/ cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code>roles/ retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code>roles/ retail.merchantCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a> ( <code>roles/ edgecontainer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a> ( <code>roles/ spectrumsas.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceusage.services.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code>roles/ actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code>roles/ actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code>roles/ dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.editor">Cloud Memorystore Redis Editor</a> ( <code>roles/ redis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.viewer">Cloud Memorystore Redis Viewer</a> ( <code>roles/ redis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code>roles/ artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code>roles/ fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code>roles/ fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code>roles/ aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code>roles/ aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/flow#aisandbox.serviceAgent">FlowService Service Agent</a> ( <code>roles/ aisandbox.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a> ( <code>roles/ automl.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code>roles/ clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code>roles/ datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.serviceAgent">Data Studio Service Agent</a> ( <code>roles/ datastudio.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.serviceAgent">External Exposure Service Agent</a> ( <code>roles/ externalexposure.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappcheck#firebaseappcheck.serviceAgent">Firebase App Check Service Agent</a> ( <code>roles/ firebaseappcheck.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code>roles/ firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.serviceAgent">Firebase Crashlytics Service Agent</a> ( <code>roles/ firebasecrashlytics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.serviceAgent">Firebase Realtime Database Service Agent</a> ( <code>roles/ firebasedatabase.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code>roles/ firebasedataconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase AI Logic Service Agent</a> ( <code>roles/ firebaseml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/flow#flow.serviceAgent">Flow Service Agent</a> ( <code>roles/ flow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.controlPlaneMachineServiceAgent">Anthos Multi-Cloud Control Plane Machine Service Agent</a> ( <code>roles/ gkemulticloud.controlPlaneMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.nodePoolMachineServiceAgent">Anthos Multi-Cloud Node Pool Machine Service Agent</a> ( <code>roles/ gkemulticloud.nodePoolMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code>roles/ krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a> ( <code>roles/ looker.restrictedServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.serviceAgent">(Legacy) Looker Service Agent</a> ( <code>roles/ looker.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code>roles/ securedlandingzone.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a> ( <code>roles/ securesourcemanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.serviceAgent">StorageInsights Service Agent</a> ( <code>roles/ storageinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code>roles/ workflows.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code>roles/ workloadcertificate.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code>roles/ workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceusage.values.test</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.viewer">Web Security Scanner Viewer</a> ( <code>roles/ cloudsecurityscanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.admin">Composer Administrator</a> ( <code>roles/ composer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.user">Composer User</a> ( <code>roles/ composer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code>roles/ androidmanagement.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayAdmin">Connect Gateway Admin</a> ( <code>roles/ gkehub.gatewayAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayEditor">Connect Gateway Editor</a> ( <code>roles/ gkehub.gatewayEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.gatewayReader">Connect Gateway Reader</a> ( <code>roles/ gkehub.gatewayReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a> ( <code>roles/ anthos.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a> ( <code>roles/ assuredworkloads.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a> ( <code>roles/ multiclusteringress.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
