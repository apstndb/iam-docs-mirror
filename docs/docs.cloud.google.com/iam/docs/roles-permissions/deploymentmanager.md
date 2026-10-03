---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager
title: Cloud Deployment Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Deployment Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Deployment Manager roles

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
<td>Deployment Manager Admin
<p>( <code>roles/ deploymentmanager.admin</code> )</p>
<p>Admin role for Deployment Manager.</p></td>
<td><p><code>deploymentmanager.*</code></p>
<ul>
<li><code>deploymentmanager. compositeTypes. create</code></li>
<li><code>deploymentmanager. compositeTypes. delete</code></li>
<li><code>deploymentmanager. compositeTypes. get</code></li>
<li><code>deploymentmanager. compositeTypes. list</code></li>
<li><code>deploymentmanager. compositeTypes. update</code></li>
<li><code>deploymentmanager. deployments. cancelPreview</code></li>
<li><code>deploymentmanager. deployments. create</code></li>
<li><code>deploymentmanager. deployments. delete</code></li>
<li><code>deploymentmanager. deployments. get</code></li>
<li><code>deploymentmanager. deployments. getIamPolicy</code></li>
<li><code>deploymentmanager. deployments. list</code></li>
<li><code>deploymentmanager. deployments. setIamPolicy</code></li>
<li><code>deploymentmanager. deployments. stop</code></li>
<li><code>deploymentmanager. deployments. update</code></li>
<li><code>deploymentmanager. manifests. get</code></li>
<li><code>deploymentmanager. manifests. list</code></li>
<li><code>deploymentmanager. operations. get</code></li>
<li><code>deploymentmanager. operations. list</code></li>
<li><code>deploymentmanager. resources. get</code></li>
<li><code>deploymentmanager. resources. list</code></li>
<li><code>deploymentmanager. typeProviders. create</code></li>
<li><code>deploymentmanager. typeProviders. delete</code></li>
<li><code>deploymentmanager. typeProviders. get</code></li>
<li><code>deploymentmanager. typeProviders. getType</code></li>
<li><code>deploymentmanager. typeProviders. list</code></li>
<li><code>deploymentmanager. typeProviders. listTypes</code></li>
<li><code>deploymentmanager. typeProviders. update</code></li>
<li><code>deploymentmanager.types.create</code></li>
<li><code>deploymentmanager.types.delete</code></li>
<li><code>deploymentmanager.types.get</code></li>
<li><code>deploymentmanager.types.list</code></li>
<li><code>deploymentmanager.types.update</code></li>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Deployment Manager Editor
<p>( <code>roles/ deploymentmanager.editor</code> )</p>
<p>Provides the permissions necessary to create and manage deployments.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>deploymentmanager. compositeTypes.*</code></p>
<ul>
<li><code>deploymentmanager. compositeTypes. create</code></li>
<li><code>deploymentmanager. compositeTypes. delete</code></li>
<li><code>deploymentmanager. compositeTypes. get</code></li>
<li><code>deploymentmanager. compositeTypes. list</code></li>
<li><code>deploymentmanager. compositeTypes. update</code></li>
</ul>
<p><code>deploymentmanager. deployments. cancelPreview</code></p>
<p><code>deploymentmanager. deployments. create</code></p>
<p><code>deploymentmanager. deployments. delete</code></p>
<p><code>deploymentmanager. deployments. get</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager. deployments. stop</code></p>
<p><code>deploymentmanager. deployments. update</code></p>
<p><code>deploymentmanager.manifests.*</code></p>
<ul>
<li><code>deploymentmanager. manifests. get</code></li>
<li><code>deploymentmanager. manifests. list</code></li>
</ul>
<p><code>deploymentmanager.operations.*</code></p>
<ul>
<li><code>deploymentmanager. operations. get</code></li>
<li><code>deploymentmanager. operations. list</code></li>
</ul>
<p><code>deploymentmanager.resources.*</code></p>
<ul>
<li><code>deploymentmanager. resources. get</code></li>
<li><code>deploymentmanager. resources. list</code></li>
</ul>
<p><code>deploymentmanager. typeProviders.*</code></p>
<ul>
<li><code>deploymentmanager. typeProviders. create</code></li>
<li><code>deploymentmanager. typeProviders. delete</code></li>
<li><code>deploymentmanager. typeProviders. get</code></li>
<li><code>deploymentmanager. typeProviders. getType</code></li>
<li><code>deploymentmanager. typeProviders. list</code></li>
<li><code>deploymentmanager. typeProviders. listTypes</code></li>
<li><code>deploymentmanager. typeProviders. update</code></li>
</ul>
<p><code>deploymentmanager.types.*</code></p>
<ul>
<li><code>deploymentmanager.types.create</code></li>
<li><code>deploymentmanager.types.delete</code></li>
<li><code>deploymentmanager.types.get</code></li>
<li><code>deploymentmanager.types.list</code></li>
<li><code>deploymentmanager.types.update</code></li>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Deployment Manager Viewer
<p>( <code>roles/ deploymentmanager.viewer</code> )</p>
<p>Provides read-only access to all Deployment Manager-related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>deploymentmanager. compositeTypes. get</code></p>
<p><code>deploymentmanager. compositeTypes. list</code></p>
<p><code>deploymentmanager. deployments. get</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager.manifests.*</code></p>
<ul>
<li><code>deploymentmanager. manifests. get</code></li>
<li><code>deploymentmanager. manifests. list</code></li>
</ul>
<p><code>deploymentmanager.operations.*</code></p>
<ul>
<li><code>deploymentmanager. operations. get</code></li>
<li><code>deploymentmanager. operations. list</code></li>
</ul>
<p><code>deploymentmanager.resources.*</code></p>
<ul>
<li><code>deploymentmanager. resources. get</code></li>
<li><code>deploymentmanager. resources. list</code></li>
</ul>
<p><code>deploymentmanager. typeProviders. get</code></p>
<p><code>deploymentmanager. typeProviders. getType</code></p>
<p><code>deploymentmanager. typeProviders. list</code></p>
<p><code>deploymentmanager. typeProviders. listTypes</code></p>
<p><code>deploymentmanager.types.get</code></p>
<p><code>deploymentmanager.types.list</code></p>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Deployment Manager Type Editor
<p>( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p>Provides read and write access to all Type Registry resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>deploymentmanager. compositeTypes.*</code></p>
<ul>
<li><code>deploymentmanager. compositeTypes. create</code></li>
<li><code>deploymentmanager. compositeTypes. delete</code></li>
<li><code>deploymentmanager. compositeTypes. get</code></li>
<li><code>deploymentmanager. compositeTypes. list</code></li>
<li><code>deploymentmanager. compositeTypes. update</code></li>
</ul>
<p><code>deploymentmanager. operations. get</code></p>
<p><code>deploymentmanager. typeProviders.*</code></p>
<ul>
<li><code>deploymentmanager. typeProviders. create</code></li>
<li><code>deploymentmanager. typeProviders. delete</code></li>
<li><code>deploymentmanager. typeProviders. get</code></li>
<li><code>deploymentmanager. typeProviders. getType</code></li>
<li><code>deploymentmanager. typeProviders. list</code></li>
<li><code>deploymentmanager. typeProviders. listTypes</code></li>
<li><code>deploymentmanager. typeProviders. update</code></li>
</ul>
<p><code>deploymentmanager.types.*</code></p>
<ul>
<li><code>deploymentmanager.types.create</code></li>
<li><code>deploymentmanager.types.delete</code></li>
<li><code>deploymentmanager.types.get</code></li>
<li><code>deploymentmanager.types.list</code></li>
<li><code>deploymentmanager.types.update</code></li>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Deployment Manager Type Viewer
<p>( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p>Provides read-only access to all Type Registry resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>deploymentmanager. compositeTypes. get</code></p>
<p><code>deploymentmanager. compositeTypes. list</code></p>
<p><code>deploymentmanager. typeProviders. get</code></p>
<p><code>deploymentmanager. typeProviders. getType</code></p>
<p><code>deploymentmanager. typeProviders. list</code></p>
<p><code>deploymentmanager. typeProviders. listTypes</code></p>
<p><code>deploymentmanager.types.get</code></p>
<p><code>deploymentmanager.types.list</code></p>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p></td>
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
<td>Cloud Deployment Manager Service Agent
<p>( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</p>
<p>Allows Deployment Manager service to actuate resources across DM projects and folders</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>accesscontextmanager. accessLevels. create</code></p>
<p><code>accesscontextmanager. accessLevels. delete</code></p>
<p><code>accesscontextmanager. accessLevels. get</code></p>
<p><code>accesscontextmanager. accessLevels. update</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. create</code></p>
<p><code>accesscontextmanager. servicePerimeters. delete</code></p>
<p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. update</code></p>
<p><code>appengine.applications.get</code></p>
<p><code>appengine.operations.get</code></p>
<p><code>appengine.services.update</code></p>
<p><code>appengine.versions.create</code></p>
<p><code>appengine.versions.delete</code></p>
<p><code>appengine.versions.get</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. delete</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. update</code></p>
<p><code>bigquery.connections.get</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.delete</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery.datasets.update</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.routines.create</code></p>
<p><code>bigquery.routines.get</code></p>
<p><code>bigquery.routines.update</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.delete</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.setCategory</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>bigtable.instances.create</code></p>
<p><code>bigtable.instances.delete</code></p>
<p><code>bigtable.instances.get</code></p>
<p><code>bigtable.instances.update</code></p>
<p><code>bigtable.tables.create</code></p>
<p><code>bigtable.tables.delete</code></p>
<p><code>bigtable.tables.get</code></p>
<p><code>bigtable.tables.update</code></p>
<p><code>billing. resourceAssociations. create</code></p>
<p><code>billing.resourcebudgets.write</code></p>
<p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudfunctions.functions.call</code></p>
<p><code>cloudfunctions. functions. create</code></p>
<p><code>cloudfunctions. functions. delete</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions. functions. update</code></p>
<p><code>cloudfunctions.operations.get</code></p>
<p><code>cloudprivatecatalog. targets. get</code></p>
<p><code>cloudscheduler.jobs.create</code></p>
<p><code>cloudscheduler.jobs.delete</code></p>
<p><code>cloudscheduler.jobs.get</code></p>
<p><code>cloudscheduler.jobs.update</code></p>
<p><code>cloudsql.backupRuns.create</code></p>
<p><code>cloudsql.databases.*</code></p>
<ul>
<li><code>cloudsql.databases.create</code></li>
<li><code>cloudsql.databases.delete</code></li>
<li><code>cloudsql.databases.get</code></li>
<li><code>cloudsql.databases.list</code></li>
<li><code>cloudsql.databases.update</code></li>
</ul>
<p><code>cloudsql.instances.create</code></p>
<p><code>cloudsql.instances.delete</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.import</code></p>
<p><code>cloudsql.instances.restart</code></p>
<p><code>cloudsql.instances.update</code></p>
<p><code>cloudsql.sslCerts.create</code></p>
<p><code>cloudsql.sslCerts.delete</code></p>
<p><code>cloudsql.sslCerts.get</code></p>
<p><code>cloudsql.users.create</code></p>
<p><code>cloudsql.users.delete</code></p>
<p><code>cloudtasks.queues.create</code></p>
<p><code>cloudtasks.queues.delete</code></p>
<p><code>cloudtasks.queues.get</code></p>
<p><code>compute.addresses.create</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.setLabels</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.autoscalers.create</code></p>
<p><code>compute.autoscalers.delete</code></p>
<p><code>compute.autoscalers.get</code></p>
<p><code>compute.autoscalers.update</code></p>
<p><code>compute.backendBuckets.create</code></p>
<p><code>compute.backendBuckets.delete</code></p>
<p><code>compute.backendBuckets.get</code></p>
<p><code>compute.backendBuckets.update</code></p>
<p><code>compute.backendBuckets.use</code></p>
<p><code>compute.backendServices.create</code></p>
<p><code>compute.backendServices.delete</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute. backendServices. setSecurityPolicy</code></p>
<p><code>compute.backendServices.update</code></p>
<p><code>compute.backendServices.use</code></p>
<p><code>compute. disks. addResourcePolicies</code></p>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute. disks. removeResourcePolicies</code></p>
<p><code>compute.disks.resize</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.update</code></p>
<p><code>compute.disks.use</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute. externalVpnGateways. create</code></p>
<p><code>compute. externalVpnGateways. delete</code></p>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. setLabels</code></p>
<p><code>compute. externalVpnGateways. use</code></p>
<p><code>compute. firewallPolicies. create</code></p>
<p><code>compute. firewallPolicies. delete</code></p>
<p><code>compute.firewallPolicies.get</code></p>
<p><code>compute.firewalls.create</code></p>
<p><code>compute.firewalls.delete</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.firewalls.update</code></p>
<p><code>compute.forwardingRules.create</code></p>
<p><code>compute.forwardingRules.delete</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute. forwardingRules. pscCreate</code></p>
<p><code>compute. forwardingRules. pscSetLabels</code></p>
<p><code>compute. forwardingRules. setLabels</code></p>
<p><code>compute. forwardingRules. setTarget</code></p>
<p><code>compute.forwardingRules.update</code></p>
<p><code>compute.forwardingRules.use</code></p>
<p><code>compute.globalAddresses.create</code></p>
<p><code>compute. globalAddresses. createInternal</code></p>
<p><code>compute.globalAddresses.delete</code></p>
<p><code>compute. globalAddresses. deleteInternal</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute. globalAddresses. setLabels</code></p>
<p><code>compute.globalAddresses.use</code></p>
<p><code>compute. globalForwardingRules. create</code></p>
<p><code>compute. globalForwardingRules. delete</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. pscCreate</code></p>
<p><code>compute. globalForwardingRules. pscDelete</code></p>
<p><code>compute. globalForwardingRules. pscSetLabels</code></p>
<p><code>compute. globalForwardingRules. setLabels</code></p>
<p><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></p>
<p><code>compute. globalNetworkEndpointGroups. create</code></p>
<p><code>compute. globalNetworkEndpointGroups. delete</code></p>
<p><code>compute. globalNetworkEndpointGroups. get</code></p>
<p><code>compute. globalNetworkEndpointGroups. use</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.healthChecks.create</code></p>
<p><code>compute.healthChecks.delete</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.update</code></p>
<p><code>compute.healthChecks.use</code></p>
<p><code>compute. healthChecks. useReadOnly</code></p>
<p><code>compute. httpHealthChecks. create</code></p>
<p><code>compute. httpHealthChecks. delete</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute. httpHealthChecks. update</code></p>
<p><code>compute.httpHealthChecks.use</code></p>
<p><code>compute. httpHealthChecks. useReadOnly</code></p>
<p><code>compute. httpsHealthChecks. create</code></p>
<p><code>compute. httpsHealthChecks. delete</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute. httpsHealthChecks. update</code></p>
<p><code>compute.httpsHealthChecks.use</code></p>
<p><code>compute. httpsHealthChecks. useReadOnly</code></p>
<p><code>compute.images.create</code></p>
<p><code>compute.images.delete</code></p>
<p><code>compute.images.deprecate</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.setLabels</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute. instanceGroupManagers. create</code></p>
<p><code>compute. instanceGroupManagers. delete</code></p>
<p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute. instanceGroupManagers. update</code></p>
<p><code>compute. instanceGroupManagers. use</code></p>
<p><code>compute.instanceGroups.create</code></p>
<p><code>compute.instanceGroups.delete</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.update</code></p>
<p><code>compute.instanceGroups.use</code></p>
<p><code>compute. instanceTemplates. create</code></p>
<p><code>compute. instanceTemplates. delete</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute. instanceTemplates. useReadOnly</code></p>
<p><code>compute. instances. addAccessConfig</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute. instances. deleteAccessConfig</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute.instances.resume</code></p>
<p><code>compute. instances. setDeletionProtection</code></p>
<p><code>compute. instances. setDiskAutoDelete</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute. instances. setServiceAccount</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute.instances.suspend</code></p>
<p><code>compute.instances.update</code></p>
<p><code>compute. instances. updateDisplayDevice</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute. interconnectAttachments. create</code></p>
<p><code>compute. interconnectAttachments. delete</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. setLabels</code></p>
<p><code>compute. interconnectAttachments. update</code></p>
<p><code>compute.interconnects.create</code></p>
<p><code>compute.interconnects.delete</code></p>
<p><code>compute.interconnects.get</code></p>
<p><code>compute. interconnects. setLabels</code></p>
<p><code>compute.interconnects.use</code></p>
<p><code>compute. machineImages. useReadOnly</code></p>
<p><code>compute.machineTypes.get</code></p>
<p><code>compute. networkEndpointGroups. attachNetworkEndpoints</code></p>
<p><code>compute. networkEndpointGroups. create</code></p>
<p><code>compute. networkEndpointGroups. delete</code></p>
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. use</code></p>
<p><code>compute.networks.addPeering</code></p>
<p><code>compute.networks.create</code></p>
<p><code>compute.networks.delete</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute.networks.removePeering</code></p>
<p><code>compute. networks. switchToCustomMode</code></p>
<p><code>compute.networks.update</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute. organizations. disableXpnResource</code></p>
<p><code>compute. organizations. enableXpnHost</code></p>
<p><code>compute. organizations. enableXpnResource</code></p>
<p><code>compute. packetMirrorings. create</code></p>
<p><code>compute. packetMirrorings. delete</code></p>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setUsageExportBucket</code></p>
<p><code>compute. regionBackendServices. create</code></p>
<p><code>compute. regionBackendServices. delete</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. update</code></p>
<p><code>compute. regionBackendServices. use</code></p>
<p><code>compute. regionHealthChecks. create</code></p>
<p><code>compute. regionHealthChecks. delete</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. update</code></p>
<p><code>compute.regionHealthChecks.use</code></p>
<p><code>compute. regionHealthChecks. useReadOnly</code></p>
<p><code>compute. regionNetworkEndpointGroups. create</code></p>
<p><code>compute. regionNetworkEndpointGroups. delete</code></p>
<p><code>compute. regionNetworkEndpointGroups. get</code></p>
<p><code>compute. regionNetworkEndpointGroups. use</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute. regionSslCertificates. create</code></p>
<p><code>compute. regionSslCertificates. delete</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionTargetHttpProxies. create</code></p>
<p><code>compute. regionTargetHttpProxies. delete</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. use</code></p>
<p><code>compute. regionTargetHttpsProxies. create</code></p>
<p><code>compute. regionTargetHttpsProxies. delete</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. use</code></p>
<p><code>compute.regionUrlMaps.create</code></p>
<p><code>compute.regionUrlMaps.delete</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.use</code></p>
<p><code>compute.regions.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. resourcePolicies. create</code></p>
<p><code>compute. resourcePolicies. delete</code></p>
<p><code>compute.resourcePolicies.get</code></p>
<p><code>compute.resourcePolicies.use</code></p>
<p><code>compute.routers.create</code></p>
<p><code>compute.routers.delete</code></p>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.update</code></p>
<p><code>compute.routers.use</code></p>
<p><code>compute.routes.create</code></p>
<p><code>compute.routes.delete</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute. securityPolicies. create</code></p>
<p><code>compute. securityPolicies. delete</code></p>
<p><code>compute.securityPolicies.get</code></p>
<p><code>compute. securityPolicies. setLabels</code></p>
<p><code>compute. securityPolicies. update</code></p>
<p><code>compute.securityPolicies.use</code></p>
<p><code>compute. serviceAttachments. create</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute.snapshots.useReadOnly</code></p>
<p><code>compute.sslCertificates.create</code></p>
<p><code>compute.sslCertificates.delete</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslPolicies.create</code></p>
<p><code>compute.sslPolicies.delete</code></p>
<p><code>compute.sslPolicies.get</code></p>
<p><code>compute.sslPolicies.use</code></p>
<p><code>compute.subnetworks.create</code></p>
<p><code>compute.subnetworks.delete</code></p>
<p><code>compute. subnetworks. expandIpCidrRange</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.mirror</code></p>
<p><code>compute.subnetworks.update</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute. targetHttpProxies. create</code></p>
<p><code>compute. targetHttpProxies. delete</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.use</code></p>
<p><code>compute. targetHttpsProxies. create</code></p>
<p><code>compute. targetHttpsProxies. delete</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. setSslCertificates</code></p>
<p><code>compute. targetHttpsProxies. setSslPolicy</code></p>
<p><code>compute.targetHttpsProxies.use</code></p>
<p><code>compute.targetInstances.create</code></p>
<p><code>compute.targetInstances.delete</code></p>
<p><code>compute.targetInstances.get</code></p>
<p><code>compute.targetInstances.use</code></p>
<p><code>compute. targetPools. addHealthCheck</code></p>
<p><code>compute. targetPools. addInstance</code></p>
<p><code>compute.targetPools.create</code></p>
<p><code>compute.targetPools.delete</code></p>
<p><code>compute.targetPools.get</code></p>
<p><code>compute. targetPools. removeHealthCheck</code></p>
<p><code>compute. targetPools. removeInstance</code></p>
<p><code>compute.targetPools.use</code></p>
<p><code>compute. targetSslProxies. create</code></p>
<p><code>compute. targetSslProxies. delete</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute. targetSslProxies. setSslCertificates</code></p>
<p><code>compute.targetSslProxies.use</code></p>
<p><code>compute. targetTcpProxies. create</code></p>
<p><code>compute. targetTcpProxies. delete</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.use</code></p>
<p><code>compute. targetVpnGateways. create</code></p>
<p><code>compute. targetVpnGateways. delete</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute. targetVpnGateways. setLabels</code></p>
<p><code>compute.targetVpnGateways.use</code></p>
<p><code>compute.urlMaps.create</code></p>
<p><code>compute.urlMaps.delete</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.update</code></p>
<p><code>compute.urlMaps.use</code></p>
<p><code>compute.vpnGateways.create</code></p>
<p><code>compute.vpnGateways.delete</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.setLabels</code></p>
<p><code>compute.vpnGateways.use</code></p>
<p><code>compute.vpnTunnels.create</code></p>
<p><code>compute.vpnTunnels.delete</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.setLabels</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.get</code></p>
<p><code>container. backendConfigs. create</code></p>
<p><code>container. backendConfigs. delete</code></p>
<p><code>container.backendConfigs.get</code></p>
<p><code>container. clusterRoleBindings. create</code></p>
<p><code>container. clusterRoleBindings. delete</code></p>
<p><code>container. clusterRoleBindings. get</code></p>
<p><code>container.clusterRoles.bind</code></p>
<p><code>container.clusterRoles.create</code></p>
<p><code>container.clusterRoles.delete</code></p>
<p><code>container. clusterRoles. escalate</code></p>
<p><code>container.clusterRoles.get</code></p>
<p><code>container.clusters.create</code></p>
<p><code>container.clusters.delete</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container. clusters. getCredentials</code></p>
<p><code>container.clusters.update</code></p>
<p><code>container.configMaps.create</code></p>
<p><code>container.configMaps.delete</code></p>
<p><code>container.configMaps.get</code></p>
<p><code>container.configMaps.update</code></p>
<p><code>container.cronJobs.create</code></p>
<p><code>container.cronJobs.delete</code></p>
<p><code>container.cronJobs.get</code></p>
<p><code>container.cronJobs.update</code></p>
<p><code>container.daemonSets.create</code></p>
<p><code>container.daemonSets.delete</code></p>
<p><code>container.daemonSets.get</code></p>
<p><code>container.daemonSets.update</code></p>
<p><code>container.deployments.create</code></p>
<p><code>container.deployments.delete</code></p>
<p><code>container.deployments.get</code></p>
<p><code>container.deployments.update</code></p>
<p><code>container. frontendConfigs. create</code></p>
<p><code>container. frontendConfigs. delete</code></p>
<p><code>container.frontendConfigs.get</code></p>
<p><code>container. horizontalPodAutoscalers. create</code></p>
<p><code>container. horizontalPodAutoscalers. delete</code></p>
<p><code>container. horizontalPodAutoscalers. get</code></p>
<p><code>container.ingresses.create</code></p>
<p><code>container.ingresses.delete</code></p>
<p><code>container.ingresses.get</code></p>
<p><code>container.jobs.create</code></p>
<p><code>container.jobs.delete</code></p>
<p><code>container.jobs.get</code></p>
<p><code>container. managedCertificates. create</code></p>
<p><code>container. managedCertificates. delete</code></p>
<p><code>container. managedCertificates. get</code></p>
<p><code>container. mutatingWebhookConfigurations. delete</code></p>
<p><code>container. mutatingWebhookConfigurations. get</code></p>
<p><code>container.namespaces.create</code></p>
<p><code>container.namespaces.delete</code></p>
<p><code>container.namespaces.get</code></p>
<p><code>container. networkPolicies. create</code></p>
<p><code>container. networkPolicies. delete</code></p>
<p><code>container.networkPolicies.get</code></p>
<p><code>container.operations.get</code></p>
<p><code>container. podDisruptionBudgets. create</code></p>
<p><code>container. podDisruptionBudgets. delete</code></p>
<p><code>container. podDisruptionBudgets. get</code></p>
<p><code>container. podSecurityPolicies. delete</code></p>
<p><code>container. podSecurityPolicies. get</code></p>
<p><code>container. priorityClasses. create</code></p>
<p><code>container. priorityClasses. delete</code></p>
<p><code>container.priorityClasses.get</code></p>
<p><code>container. replicationControllers. create</code></p>
<p><code>container. replicationControllers. delete</code></p>
<p><code>container. replicationControllers. get</code></p>
<p><code>container.roleBindings.create</code></p>
<p><code>container.roleBindings.delete</code></p>
<p><code>container.roleBindings.get</code></p>
<p><code>container.roles.bind</code></p>
<p><code>container.roles.create</code></p>
<p><code>container.roles.delete</code></p>
<p><code>container.roles.escalate</code></p>
<p><code>container.roles.get</code></p>
<p><code>container.roles.update</code></p>
<p><code>container.secrets.create</code></p>
<p><code>container.secrets.delete</code></p>
<p><code>container.secrets.get</code></p>
<p><code>container.secrets.update</code></p>
<p><code>container. serviceAccounts. create</code></p>
<p><code>container. serviceAccounts. delete</code></p>
<p><code>container.serviceAccounts.get</code></p>
<p><code>container. serviceAccounts. update</code></p>
<p><code>container.services.create</code></p>
<p><code>container.services.delete</code></p>
<p><code>container.services.get</code></p>
<p><code>container.statefulSets.create</code></p>
<p><code>container.statefulSets.delete</code></p>
<p><code>container.statefulSets.get</code></p>
<p><code>container.statefulSets.update</code></p>
<p><code>container. storageClasses. create</code></p>
<p><code>container. storageClasses. delete</code></p>
<p><code>container.storageClasses.get</code></p>
<p><code>container. thirdPartyObjects. create</code></p>
<p><code>container. thirdPartyObjects. delete</code></p>
<p><code>container. thirdPartyObjects. get</code></p>
<p><code>container. thirdPartyObjects. update</code></p>
<p><code>container. validatingWebhookConfigurations. delete</code></p>
<p><code>container. validatingWebhookConfigurations. get</code></p>
<p><code>datacatalog.taxonomies.get</code></p>
<p><code>dataproc. autoscalingPolicies. create</code></p>
<p><code>dataproc. autoscalingPolicies. delete</code></p>
<p><code>dataproc. autoscalingPolicies. get</code></p>
<p><code>dataproc. autoscalingPolicies. use</code></p>
<p><code>dataproc.clusters.create</code></p>
<p><code>dataproc.clusters.delete</code></p>
<p><code>dataproc.clusters.get</code></p>
<p><code>dataproc.nodeGroups.create</code></p>
<p><code>dataproc.operations.get</code></p>
<p><code>dataproc. workflowTemplates. create</code></p>
<p><code>dataproc. workflowTemplates. delete</code></p>
<p><code>dataproc.workflowTemplates.get</code></p>
<p><code>deploymentmanager. compositeTypes. get</code></p>
<p><code>deploymentmanager. deployments. create</code></p>
<p><code>deploymentmanager. deployments. delete</code></p>
<p><code>deploymentmanager. deployments. get</code></p>
<p><code>deploymentmanager. deployments. update</code></p>
<p><code>deploymentmanager. operations. get</code></p>
<p><code>deploymentmanager. typeProviders. create</code></p>
<p><code>deploymentmanager. typeProviders. delete</code></p>
<p><code>deploymentmanager. typeProviders. get</code></p>
<p><code>deploymentmanager. typeProviders. update</code></p>
<p><code>dns.changes.*</code></p>
<ul>
<li><code>dns.changes.create</code></li>
<li><code>dns.changes.get</code></li>
<li><code>dns.changes.list</code></li>
</ul>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.managedZones.update</code></p>
<p><code>dns. networks. bindPrivateDNSZone</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>dns.policies.delete</code></p>
<p><code>dns.policies.get</code></p>
<p><code>dns.resourceRecordSets.create</code></p>
<p><code>dns.resourceRecordSets.delete</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.resourceRecordSets.update</code></p>
<p><code>file.instances.create</code></p>
<p><code>file.instances.delete</code></p>
<p><code>file.instances.get</code></p>
<p><code>file.instances.update</code></p>
<p><code>file.operations.get</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebase.projects.update</code></p>
<p><code>firebaseanalytics. resources. googleAnalyticsEdit</code></p>
<p><code>iam.roles.create</code></p>
<p><code>iam.roles.delete</code></p>
<p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.roles.update</code></p>
<p><code>iam.serviceAccountKeys.delete</code></p>
<p><code>iam.serviceAccountKeys.get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.delete</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam.serviceAccounts.update</code></p>
<p><code>logging.buckets.update</code></p>
<p><code>logging.exclusions.create</code></p>
<p><code>logging.exclusions.delete</code></p>
<p><code>logging.exclusions.get</code></p>
<p><code>logging.exclusions.update</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logMetrics.create</code></p>
<p><code>logging.logMetrics.delete</code></p>
<p><code>logging.logMetrics.get</code></p>
<p><code>logging.logMetrics.update</code></p>
<p><code>logging. notificationRules. create</code></p>
<p><code>logging.sinks.create</code></p>
<p><code>logging.sinks.delete</code></p>
<p><code>logging.sinks.get</code></p>
<p><code>logging.sinks.update</code></p>
<p><code>monitoring. alertPolicies. create</code></p>
<p><code>monitoring. alertPolicies. delete</code></p>
<p><code>monitoring.alertPolicies.get</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring. alertPolicies. update</code></p>
<p><code>monitoring.dashboards.create</code></p>
<p><code>monitoring.dashboards.delete</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.update</code></p>
<p><code>monitoring.groups.create</code></p>
<p><code>monitoring.groups.delete</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.update</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. delete</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. notificationChannels. create</code></p>
<p><code>monitoring. notificationChannels. delete</code></p>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. update</code></p>
<p><code>monitoring. uptimeCheckConfigs. create</code></p>
<p><code>monitoring. uptimeCheckConfigs. delete</code></p>
<p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. update</code></p>
<p><code>networksecurity. serverTlsPolicies. use</code></p>
<p><code>pubsub.schemas.attach</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>redis.instances.create</code></p>
<p><code>redis.instances.delete</code></p>
<p><code>redis.instances.get</code></p>
<p><code>redis.instances.update</code></p>
<p><code>redis.instances.updateAuth</code></p>
<p><code>redis.operations.get</code></p>
<p><code>resourcemanager.folders.create</code></p>
<p><code>resourcemanager.folders.delete</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager.folders.update</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager. projects. create</code></p>
<p><code>resourcemanager. projects. createBillingAssignment</code></p>
<p><code>resourcemanager. projects. delete</code></p>
<p><code>resourcemanager. projects. deleteBillingAssignment</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.projects.move</code></p>
<p><code>resourcemanager. projects. update</code></p>
<p><code>resourcemanager. projects. updateLiens</code></p>
<p><code>resourcemanager. tagHolds. create</code></p>
<p><code>resourcemanager. tagHolds. delete</code></p>
<p><code>resourcemanager. tagValueBindings.*</code></p>
<ul>
<li><code>resourcemanager. tagValueBindings. create</code></li>
<li><code>resourcemanager. tagValueBindings. delete</code></li>
</ul>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>runtimeconfig.configs.create</code></p>
<p><code>runtimeconfig.configs.delete</code></p>
<p><code>runtimeconfig.configs.get</code></p>
<p><code>runtimeconfig.configs.list</code></p>
<p><code>runtimeconfig.configs.update</code></p>
<p><code>runtimeconfig.variables.create</code></p>
<p><code>runtimeconfig.variables.delete</code></p>
<p><code>runtimeconfig.variables.get</code></p>
<p><code>runtimeconfig.variables.list</code></p>
<p><code>runtimeconfig.variables.update</code></p>
<p><code>runtimeconfig.waiters.create</code></p>
<p><code>runtimeconfig.waiters.delete</code></p>
<p><code>runtimeconfig.waiters.get</code></p>
<p><code>runtimeconfig.waiters.list</code></p>
<p><code>servicedirectory. namespaces. associatePrivateZone</code></p>
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. namespaces. delete</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicemanagement. services. bind</code></p>
<p><code>servicenetworking. operations. get</code></p>
<p><code>servicenetworking. services. addPeering</code></p>
<p><code>servicenetworking.services.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.services.disable</code></p>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>source.repos.create</code></p>
<p><code>spanner.databaseOperations.get</code></p>
<p><code>spanner.databases.create</code></p>
<p><code>spanner.databases.drop</code></p>
<p><code>spanner.databases.get</code></p>
<p><code>spanner.databases.updateDdl</code></p>
<p><code>spanner.instanceOperations.get</code></p>
<p><code>spanner.instances.create</code></p>
<p><code>spanner.instances.delete</code></p>
<p><code>spanner.instances.get</code></p>
<p><code>spanner.instances.update</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.hmacKeys.create</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p>
<p><code>vpcaccess.connectors.create</code></p>
<p><code>vpcaccess.connectors.delete</code></p>
<p><code>vpcaccess.operations.get</code></p>
<p><code>workflows.operations.get</code></p>
<p><code>workflows.workflows.create</code></p>
<p><code>workflows.workflows.delete</code></p>
<p><code>workflows.workflows.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Deployment Manager permissions

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
<td><code>deploymentmanager. compositeTypes. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. compositeTypes. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. compositeTypes. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. compositeTypes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. compositeTypes. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. deployments. cancelPreview</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. deployments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. deployments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. deployments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. deployments. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. deployments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. deployments. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. deployments. stop</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. deployments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. manifests. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. manifests. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. resources. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. resources. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. typeProviders. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. typeProviders. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. typeProviders. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. typeProviders. getType</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. typeProviders. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager. typeProviders. listTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager. typeProviders. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager.types.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager.types.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager.types.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>deploymentmanager.types.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>deploymentmanager.types.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
